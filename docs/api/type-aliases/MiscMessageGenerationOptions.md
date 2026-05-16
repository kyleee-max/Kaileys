# Type Alias: MiscMessageGenerationOptions

> **MiscMessageGenerationOptions**: `MinimalRelayOptions` & `object`

Defined in: [src/Types/Message.ts:327](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Message.ts#L327)

## Type declaration

### backgroundColor?

> `optional` **backgroundColor**: `string`

backgroundcolor for status

### broadcast?

> `optional` **broadcast**: `boolean`

if it is broadcast

### ephemeralExpiration?

> `optional` **ephemeralExpiration**: `number` \| `string`

disappearing messages settings

### font?

> `optional` **font**: `number`

font type for status

### mediaUploadTimeoutMs?

> `optional` **mediaUploadTimeoutMs**: `number`

timeout for media upload to WA server

### quoted?

> `optional` **quoted**: [`WAMessage`](WAMessage.md)

the message you want to quote

### statusJidList?

> `optional` **statusJidList**: `string`[]

jid list of participants for status@broadcast

### timestamp?

> `optional` **timestamp**: `Date`

optional, if you want to manually set the timestamp of the message
