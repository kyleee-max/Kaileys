# Type Alias: WAMediaUploadFunction()

> **WAMediaUploadFunction**: (`encFilePath`, `opts`) => `Promise`\<\{ `directPath`: `string`; `fbid`: `number`; `mediaUrl`: `string`; `meta_hmac`: `string`; `ts`: `number`; \}\>

Defined in: [src/Types/Message.ts:349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Message.ts#L349)

## Parameters

### encFilePath

`string`

### opts

#### fileEncSha256B64

`string`

#### mediaType

[`MediaType`](MediaType.md)

#### timeoutMs?

`number`

## Returns

`Promise`\<\{ `directPath`: `string`; `fbid`: `number`; `mediaUrl`: `string`; `meta_hmac`: `string`; `ts`: `number`; \}\>
