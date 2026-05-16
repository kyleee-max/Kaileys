# <div align='center'>Kaileys</div>

<div align='center'>

[![npm version](https://img.shields.io/npm/v/kaileys.svg)](https://www.npmjs.com/package/kaileys)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Downloads](https://img.shields.io/npm/dm/kaileys.svg)](https://www.npmjs.com/package/kaileys)

</div>

---

## ✨ Fitur Utama

- 🚀 **Modern & Cepat** - Dibangun di atas WhiskeySockets/Baileys dengan teknologi terbaru
- 🔧 **Perbaikan @lid & @jid** - Mengatasi masalah @lid ke @pn di grup WhatsApp
- 📱 **Dukungan Multi-Device** - Mendukung koneksi multi-device WhatsApp
- 🔐 **Enkripsi End-to-End** - Komunikasi terenkripsi penuh
- 📨 **Semua Jenis Pesan** - Dukung teks, media, polling, dll.
- 🔑 **Custom Pairing Code** - Support pairing code kustom (default: `KAELZDEV`)
- 📢 **Auto Follow Saluran Update** - Otomatis follow saluran update Kaileys (lihat [Transparansi](#-transparansi))

---

## ⚠️ Peringatan

Proyek ini tidak berafiliasi, terkait, diotorisasi, didukung, atau terhubung secara resmi dengan WhatsApp atau anak perusahaannya. Situs resmi WhatsApp ada di whatsapp.com.

Pengelola Kaileys tidak mendukung penggunaan aplikasi ini untuk melanggar Ketentuan Layanan WhatsApp. Kami menekankan tanggung jawab pribadi pengguna untuk menggunakan secara adil dan bertanggung jawab.

Gunakan dengan bijak. Hindari spam. Jangan gunakan otomatisasi berlebihan.

---

## 📢 Transparansi

Kaileys secara otomatis mem-follow **2 saluran WhatsApp** milik Kaileys saat bot pertama kali terhubung. Saluran ini digunakan untuk:

- 📣 Informasi update versi terbaru
- 🐛 Pemberitahuan bug kritis
- 📋 Changelog & release notes

**Jika Anda tidak ingin fitur ini**, gunakan versi original [@whiskeysockets/baileys](https://www.npmjs.com/package/@whiskeysockets/baileys).

---

## 📦 Instalasi

### Versi Stabil (Direkomendasikan)

```bash
npm i kaileys
```

### Versi Edge (Fitur Terbaru)

```bash
npm i kaileys@latest
# atau
yarn add kaileys@latest
```

### Impor di Kode

```javascript
const { default: makeWASocket } = require("kaileys")
// atau ES6
import makeWASocket from "kaileys"
```

---

## 🚀 Mulai Cepat

### Contoh Dasar

```javascript
const { default: makeWASocket, DisconnectReason, useMultiFileAuthState } = require('kaileys')
const { Boom } = require('@hapi/boom')

async function connectToWhatsApp() {
    const { state, saveCreds } = await useMultiFileAuthState('auth_info_kaileys')
    
    const sock = makeWASocket({
        auth: state,
        printQRInTerminal: true,
        browser: ['Kaileys', 'Desktop', '3.0']
    })

    sock.ev.on('connection.update', (update) => {
        const { connection, lastDisconnect } = update
        if(connection === 'close') {
            const shouldReconnect = (lastDisconnect?.error as Boom)?.output?.statusCode !== DisconnectReason.loggedOut
            console.log('Koneksi tertutup karena ', lastDisconnect.error, ', reconnecting ', shouldReconnect)
            if(shouldReconnect) {
                connectToWhatsApp()
            }
        } else if(connection === 'open') {
            console.log('✅ Berhasil terhubung ke WhatsApp!')
        }
    })

    sock.ev.on('messages.upsert', async ({ messages }) => {
        for (const m of messages) {
            if (!m.message) continue
            console.log('📱 Pesan baru:', JSON.stringify(m, undefined, 2))
            await sock.sendMessage(m.key.remoteJid!, { 
                text: 'Halo! Saya bot WhatsApp menggunakan Kaileys 🤖' 
            })
        }
    })

    sock.ev.on('creds.update', saveCreds)
}

connectToWhatsApp()
```

---

## 📋 Daftar Isi

- [Koneksi Akun](#-koneksi-akun)
- [Simpan Info Auth](#-simpan-info-auth)
- [Implementasi Data Store](#️-implementasi-data-store)
- [Kirim Pesan](#-kirim-pesan)
- [Ubah Pesan](#️-ubah-pesan)
- [Manipulasi Pesan Media](#️-manipulasi-pesan-media)
- [Grup](#-grup)
- [Privasi](#-privasi)
- [Daftar Siaran & Cerita](#-daftar-siaran--cerita)
- [Fungsi Kustom](#️-fungsi-kustom)

---

## 🔌 Koneksi Akun

WhatsApp menyediakan API multi-device yang memungkinkan Kaileys terautentikasi sebagai klien WhatsApp sekunder melalui QR code atau pairing code.

### Hubungkan dengan QR Code

> [!TIP]  
> Sesuaikan nama browser menggunakan konstanta `Browsers`. Lihat konfigurasi yang tersedia di bawah.

```javascript
const { default: makeWASocket, Browsers } = require("kaileys")

const sock = makeWASocket({
    browser: Browsers.ubuntu('My App'),
    printQRInTerminal: true
})
```

Setelah koneksi berhasil, QR code akan muncul di terminal. Pindai dengan WhatsApp di ponsel Anda untuk login.

### Hubungkan dengan Pairing Code

> [!IMPORTANT]  
> Pairing code bukan bagian dari Mobile API. Ini memungkinkan koneksi WhatsApp Web tanpa QR code, tapi hanya satu perangkat.

Nomor telepon harus tanpa `+`, `()`, atau `-`, dan sertakan kode negara.

```javascript
const { default: makeWASocket } = require("kaileys")

const sock = makeWASocket({
    printQRInTerminal: false
})

// Pairing dengan kode default (KAELZDEV)
if (!sock.authState.creds.registered) {
    const number = '6285134816783'
    const code = await sock.requestPairingCode(number)
    console.log('🔑 Kode Pairing:', code) // Output: KAELZDEV
}

// Pairing dengan kode kustom (harus 8 karakter)
if (!sock.authState.creds.registered) {
    const pair = "MYCODE12" // tepat 8 karakter
    const number = '6285134816783'
    const code = await sock.requestPairingCode(number, pair)
    console.log('🔑 Kode Pairing Kustom:', code)
}
```

> [!NOTE]
> Default pairing code Kaileys adalah `KAELZDEV`. Kode kustom harus tepat **8 karakter**.

### Terima Riwayat Lengkap

1. Setel `syncFullHistory` ke `true`.
2. Untuk koneksi seperti desktop (riwayat pesan lebih banyak), gunakan:

```javascript
const { default: makeWASocket, Browsers } = require("kaileys")

const sock = makeWASocket({
    browser: Browsers.macOS('Desktop'),
    syncFullHistory: true
})
```

---

## ⚙️ Catatan Penting Konfigurasi Socket

### Caching Metadata Grup (Direkomendasikan)

```javascript
const { default: makeWASocket } = require("kaileys")
const NodeCache = require('node-cache')

const groupCache = new NodeCache({ stdTTL: 5 * 60, useClones: false })

const sock = makeWASocket({
    cachedGroupMetadata: async (jid) => groupCache.get(jid)
})

sock.ev.on('groups.update', async ([event]) => {
    const metadata = await sock.groupMetadata(event.id)
    groupCache.set(event.id, metadata)
})

sock.ev.on('group-participants.update', async (event) => {
    const metadata = await sock.groupMetadata(event.id)
    groupCache.set(event.id, metadata)
})
```

### Perbaiki Sistem Retry & Dekripsi Vote Poll

```javascript
const sock = makeWASocket({
    getMessage: async (key) => await getMessageFromStore(key)
})
```

### Terima Notifikasi di Aplikasi WhatsApp

```javascript
const sock = makeWASocket({
    markOnlineOnConnect: false
})
```

---

## 💾 Simpan Info Auth

```javascript
const makeWASocket = require("kaileys").default
const { useMultiFileAuthState } = require("kaileys")

async function connect() {
    const { state, saveCreds } = await useMultiFileAuthState('auth_info_kaileys')
    const sock = makeWASocket({ auth: state })
    sock.ev.on('creds.update', saveCreds)
}

connect()
```

> [!IMPORTANT]  
> `useMultiFileAuthState` menyimpan status auth di folder. Untuk produksi, gunakan database SQL/No-SQL.

---

## 🗄️ Implementasi Data Store

Kaileys tidak menyertakan penyimpanan default untuk obrolan, kontak, atau pesan. Namun, implementasi in-memory sederhana disediakan.

> [!IMPORTANT]  
> Sangat direkomendasikan membangun data store sendiri — menyimpan seluruh riwayat obrolan di memori sangat boros RAM.

```javascript
const makeWASocket = require("kaileys").default
const { makeInMemoryStore } = require("kaileys")

const store = makeInMemoryStore({ })

store.readFromFile('./kaileys_store.json')

setInterval(() => {
    store.writeToFile('./kaileys_store.json')
}, 10_000)

const sock = makeWASocket({ })
store.bind(sock.ev)

sock.ev.on('chats.upsert', () => {
    console.log('dapat obrolan', store.chats.all())
})

sock.ev.on('contacts.upsert', () => {
    console.log('dapat kontak', Object.values(store.contacts))
})
```

---

## 🆔 Penjelasan ID WhatsApp

| Tipe | Format | Contoh |
|------|--------|--------|
| Personal | `[kode negara][nomor]@s.whatsapp.net` | `6281234567890@s.whatsapp.net` |
| Grup | `[id]@g.us` | `123456789-123345@g.us` |
| Siaran | `[timestamp]@broadcast` | - |
| Cerita | `status@broadcast` | - |

---

## 📤 Kirim Pesan

### Pesan Teks

```javascript
await sock.sendMessage(jid, { text: 'halo dunia' })
```

### Pesan Kutipan

```javascript
await sock.sendMessage(jid, { text: 'halo dunia' }, { quoted: message })
```

### Sebut Pengguna

```javascript
await sock.sendMessage(jid, {
    text: '@12345678901',
    mentions: ['12345678901@s.whatsapp.net']
})
```

### Teruskan Pesan

```javascript
const msg = getMessageFromStore()
await sock.sendMessage(jid, { forward: msg })
```

### Pesan Lokasi

```javascript
await sock.sendMessage(jid, {
    location: {
        degreesLatitude: 24.121231,
        degreesLongitude: 55.1121221
    }
})
```

### Pesan Kontak

```javascript
const vcard = 'BEGIN:VCARD\n'
            + 'VERSION:3.0\n'
            + 'FN:Jeff Singh\n'
            + 'ORG:Ashoka Uni;\n'
            + 'TEL;type=CELL;type=VOICE;waid=911234567890:+91 12345 67890\n'
            + 'END:VCARD'

await sock.sendMessage(id, {
    contacts: {
        displayName: 'Jeff',
        contacts: [{ vcard }]
    }
})
```

### Pesan Reaksi

```javascript
await sock.sendMessage(jid, {
    react: {
        text: '💖', // kosongkan untuk hapus reaksi
        key: message.key
    }
})
```

### Pin Pesan

| Waktu | Detik |
|-------|-------|
| 24 jam | 86.400 |
| 7 hari | 604.800 |
| 30 hari | 2.592.000 |

```javascript
await sock.sendMessage(jid, {
    pin: {
        type: 1, // 0 untuk hapus
        time: 86400,
        key: message.key
    }
})
```

### Pesan Poll

```javascript
await sock.sendMessage(jid, {
    poll: {
        name: 'Poll Saya',
        values: ['Opsi 1', 'Opsi 2'],
        selectableCount: 1,
        toAnnouncementGroup: false
    }
})
```

### Kirim dengan Pratinjau Tautan

Tambahkan `link-preview-js` terlebih dahulu:

```bash
npm i link-preview-js
```

```javascript
await sock.sendMessage(jid, {
    text: 'Halo, ini dikirim menggunakan https://npmjs.com/package/kaileys'
})
```

### Pesan Media

> [!NOTE] Bisa gunakan `{ stream: Stream }`, `{ url: Url }`, atau Buffer langsung.

#### Gif

```javascript
await sock.sendMessage(jid, {
    video: fs.readFileSync('Media/ma_gif.mp4'),
    caption: 'halo dunia',
    gifPlayback: true
})
```

#### Video

```javascript
await sock.sendMessage(id, {
    video: { url: './Media/ma_gif.mp4' },
    caption: 'halo dunia',
    ptv: false // true untuk video note
})
```

#### Audio

```javascript
await sock.sendMessage(jid, {
    audio: { url: './Media/audio.mp3' },
    mimetype: 'audio/mp4'
})
```

#### Gambar

```javascript
await sock.sendMessage(id, {
    image: { url: './Media/ma_img.png' },
    caption: 'halo dunia'
})
```

#### View Once

```javascript
await sock.sendMessage(id, {
    image: { url: './Media/ma_img.png' },
    viewOnce: true,
    caption: 'halo dunia'
})
```

---

## ✏️ Ubah Pesan

### Hapus Pesan (untuk semua)

```javascript
const msg = await sock.sendMessage(jid, { text: 'halo dunia' })
await sock.sendMessage(jid, { delete: msg.key })
```

### Edit Pesan

```javascript
await sock.sendMessage(jid, {
    text: 'teks terupdate di sini',
    edit: response.key,
})
```

---

## 🖼️ Manipulasi Pesan Media

### Unduh Pesan Media

```javascript
import { createWriteStream } from 'fs'
import { downloadMediaMessage, getContentType } from 'kaileys'

sock.ev.on('messages.upsert', async ({ messages: [m] }) => {
    if (!m.message) return
    const messageType = getContentType(m)

    if (messageType === 'imageMessage') {
        const stream = await downloadMediaMessage(
            m,
            'stream',
            { },
            {
                logger,
                reuploadRequest: sock.updateMediaMessage
            }
        )
        const writeStream = createWriteStream('./my-download.jpeg')
        stream.pipe(writeStream)
    }
})
```

### Unggah Ulang Pesan Media

```javascript
await sock.updateMediaMessage(msg)
```

---

## 📞 Tolak Panggilan

```javascript
await sock.rejectCall(callId, callFrom)
```

---

## 💬 Status Kirim

### Baca Pesan

```javascript
await sock.readMessages([key])
```

### Update Kehadiran

`presence` bisa: `available`, `composing`, `recording`, `paused`, `unavailable`.

```javascript
await sock.sendPresenceUpdate('available', jid)
```

---

## 📁 Ubah Obrolan

> [!IMPORTANT] Jika salah update, WA bisa logout dari semua perangkat.

### Arsipkan Obrolan

```javascript
const lastMsgInChat = await getLastMessageInChat(jid)
await sock.chatModify({ archive: true, lastMessages: [lastMsgInChat] }, jid)
```

### Bisukan/Buka Bisukan

| Waktu | Milidetik |
|-------|-----------|
| Hapus | null |
| 8 jam | 86.400.000 |
| 7 hari | 604.800.000 |

```javascript
await sock.chatModify({ mute: 8 * 60 * 60 * 1000 }, jid) // bisukan 8 jam
await sock.chatModify({ mute: null }, jid) // buka bisukan
```

### Tandai Dibaca/Tidak Dibaca

```javascript
const lastMsgInChat = await getLastMessageInChat(jid)
await sock.chatModify({ markRead: false, lastMessages: [lastMsgInChat] }, jid)
```

### Hapus Pesan untuk Saya

```javascript
await sock.chatModify({
    clear: {
        messages: [{ id: 'ATWYHDNNWU81732J', fromMe: true, timestamp: '1654823909' }]
    }
}, jid)
```

### Hapus Obrolan

```javascript
const lastMsgInChat = await getLastMessageInChat(jid)
await sock.chatModify({
    delete: true,
    lastMessages: [{ key: lastMsgInChat.key, messageTimestamp: lastMsgInChat.messageTimestamp }]
}, jid)
```

### Pin/Hapus Pin

```javascript
await sock.chatModify({ pin: true }, jid) // atau false
```

### Bintangi/Hapus Bintang

```javascript
await sock.chatModify({
    star: {
        messages: [{ id: 'messageID', fromMe: true }],
        star: true
    }
}, jid)
```

### Pesan Menghilang

| Waktu | Detik |
|-------|-------|
| Hapus | 0 |
| 24 jam | 86.400 |
| 7 hari | 604.800 |
| 90 hari | 7.776.000 |

```javascript
await sock.sendMessage(jid, { disappearingMessagesInChat: WA_DEFAULT_EPHEMERAL })
await sock.sendMessage(jid, { text: 'halo' }, { ephemeralExpiration: WA_DEFAULT_EPHEMERAL })
await sock.sendMessage(jid, { disappearingMessagesInChat: false }) // matikan
```

---

## 👤 Query Pengguna

### Periksa ID Ada di WhatsApp

```javascript
const [result] = await sock.onWhatsApp(jid)
if (result.exists) console.log(`${jid} ada di WhatsApp, sebagai jid: ${result.jid}`)
```

### Query Riwayat Obrolan

```javascript
const msg = await getOldestMessageInChat(jid)
await sock.fetchMessageHistory(50, msg.key, msg.messageTimestamp)
```

### Ambil Status

```javascript
const status = await sock.fetchStatus(jid)
console.log('status: ' + status)
```

### Ambil Foto Profil

```javascript
const ppUrl = await sock.profilePictureUrl(jid) // resolusi rendah
const ppUrl = await sock.profilePictureUrl(jid, 'image') // resolusi tinggi
```

### Ambil Kehadiran

```javascript
sock.ev.on('presence.update', console.log)
await sock.presenceSubscribe(jid)
```

---

## 🔄 Ubah Profil

```javascript
await sock.updateProfileStatus('Halo Dunia!')
await sock.updateProfileName('Nama Saya')
await sock.updateProfilePicture(jid, { url: './new-profile-picture.jpeg' })
await sock.removeProfilePicture(jid)
```

---

## 👥 Grup

### Buat Grup

```javascript
const group = await sock.groupCreate('Grup Saya', ['1234@s.whatsapp.net', '4564@s.whatsapp.net'])
console.log('grup dibuat dengan id: ' + group.gid)
```

### Tambah/Hapus/Turunkan/Naikkan

```javascript
await sock.groupParticipantsUpdate(
    jid,
    ['abcd@s.whatsapp.net', 'efgh@s.whatsapp.net'],
    'add' // 'remove', 'demote', 'promote'
)
```

### Ubah Pengaturan

```javascript
await sock.groupSettingUpdate(jid, 'announcement') // hanya admin kirim
await sock.groupSettingUpdate(jid, 'not_announcement') // semua bisa kirim
await sock.groupSettingUpdate(jid, 'locked') // hanya admin ubah info
await sock.groupSettingUpdate(jid, 'unlocked') // semua bisa ubah info
```

### Kode Undangan

```javascript
const code = await sock.groupInviteCode(jid)
console.log('link: https://chat.whatsapp.com/' + code)

await sock.groupRevokeInvite(jid) // cabut kode

const response = await sock.groupAcceptInvite(code) // gabung via kode
```

### Query Metadata

```javascript
const metadata = await sock.groupMetadata(jid)
console.log(metadata.id + ', judul: ' + metadata.subject + ', deskripsi: ' + metadata.desc)
```

### Permintaan Gabung

```javascript
const response = await sock.groupRequestParticipantsList(jid)
await sock.groupRequestParticipantsUpdate(jid, ['abcd@s.whatsapp.net'], 'approve') // atau 'reject'
```

---

## 🔒 Privasi

```javascript
await sock.updateBlockStatus(jid, 'block') // blokir
await sock.updateBlockStatus(jid, 'unblock') // buka blokir

const privacySettings = await sock.fetchPrivacySettings(true)
const blocklist = await sock.fetchBlocklist()

await sock.updateLastSeenPrivacy('all') // 'contacts' | 'contact_blacklist' | 'none'
await sock.updateOnlinePrivacy('all') // 'match_last_seen'
await sock.updateProfilePicturePrivacy('all')
await sock.updateStatusPrivacy('all')
await sock.updateReadReceiptsPrivacy('all')
await sock.updateGroupsAddPrivacy('all')
```

---

## 📢 Daftar Siaran & Cerita

```javascript
await sock.sendMessage(
    jid,
    { image: { url: url }, caption: caption },
    { backgroundColor, font, statusJidList, broadcast: true }
)

const bList = await sock.getBroadcastListInfo('1234@broadcast')
console.log(`nama: ${bList.name}, penerima: ${bList.recipients}`)
```

---

## 🛠️ Fungsi Kustom

### Aktifkan Level Debug

```javascript
const sock = makeWASocket({
    logger: P({ level: 'debug' }),
})
```

### Daftarkan Callback WebSocket

```javascript
sock.ws.on('CB:edge_routing', (node) => { })
sock.ws.on('CB:edge_routing,id:abcd', (node) => { })
sock.ws.on('CB:edge_routing,id:abcd,routing_info', (node) => { })
```

---

## 💡 Tips & Praktik Terbaik

- **Gunakan Caching** — Cache metadata grup untuk performa lebih baik
- **Tangani Rekoneksi** — Implementasikan auto-reconnect untuk kestabilan
- **Kelola Store** — Gunakan database (MongoDB, PostgreSQL) untuk produksi
- **Penanganan Error** — Bungkus panggilan socket dengan try-catch
- **Batas Rate** — Hormati batas WhatsApp untuk hindari ban
- **Keamanan** — Jangan bagikan kredensial auth; gunakan variabel lingkungan

---

## 📄 Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat [LICENSE](LICENSE) untuk info lebih lanjut.

---

<div align="center">
  Fork dan dimodifikasi oleh Kaels.<br>
  Kaileys - WhatsApp Web API Modern | Based on <a href="https://github.com/WhiskeySockets/Baileys">WhiskeySockets/Baileys</a>
</div>
