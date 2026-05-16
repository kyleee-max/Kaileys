# Function: encryptedStream()

> **encryptedStream**(`media`, `mediaType`, `__namedParameters`): `Promise`\<\{ `encFilePath`: `string`; `fileEncSha256`: `NonSharedBuffer`; `fileLength`: `number`; `fileSha256`: `NonSharedBuffer`; `mac`: `Buffer`\<`ArrayBuffer`\>; `mediaKey`: `NonSharedBuffer`; `originalFilePath`: `undefined` \| `string`; \}\>

Defined in: [src/Utils/messages-media.ts:385](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/messages-media.ts#L385)

## Parameters

### media

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### mediaType

`"ppic"` | `"product"` | `"image"` | `"video"` | `"sticker"` | `"thumbnail-document"` | `"audio"` | `"thumbnail-image"` | `"biz-cover-photo"` | `"thumbnail-video"` | `"thumbnail-link"` | `"gif"` | `"md-app-state"` | `"md-msg-hist"` | `"document"` | `"ptt"` | `"product-catalog-image"` | `"payment-bg-image"` | `"ptv"`

### \_\_namedParameters

`EncryptedStreamOptions` = `{}`

## Returns

`Promise`\<\{ `encFilePath`: `string`; `fileEncSha256`: `NonSharedBuffer`; `fileLength`: `number`; `fileSha256`: `NonSharedBuffer`; `mac`: `Buffer`\<`ArrayBuffer`\>; `mediaKey`: `NonSharedBuffer`; `originalFilePath`: `undefined` \| `string`; \}\>
