# Function: downloadEncryptedContent()

> **downloadEncryptedContent**(`downloadUrl`, `__namedParameters`, `__namedParameters`): `Promise`\<`Transform`\>

Defined in: [src/Utils/messages-media.ts:553](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/messages-media.ts#L553)

Decrypts and downloads an AES256-CBC encrypted file given the keys.
Assumes the SHA256 of the plaintext is appended to the end of the ciphertext

## Parameters

### downloadUrl

`string`

### \_\_namedParameters

[`MediaDecryptionKeyInfo`](../type-aliases/MediaDecryptionKeyInfo.md)

### \_\_namedParameters

[`MediaDownloadOptions`](../type-aliases/MediaDownloadOptions.md) = `{}`

## Returns

`Promise`\<`Transform`\>
