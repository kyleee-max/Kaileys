# Function: getStream()

> **getStream**(`item`, `opts`?): `Promise`\<\{ `stream`: `Readable`; `type`: `"buffer"`; \} \| \{ `stream`: `Readable`; `type`: `"readable"`; \} \| \{ `stream`: `Readable`; `type`: `"remote"`; \} \| \{ `stream`: `ReadStream`; `type`: `"file"`; \}\>

Defined in: [src/Utils/messages-media.ts:304](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/messages-media.ts#L304)

## Parameters

### item

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

### opts?

`RequestInit` & `object`

## Returns

`Promise`\<\{ `stream`: `Readable`; `type`: `"buffer"`; \} \| \{ `stream`: `Readable`; `type`: `"readable"`; \} \| \{ `stream`: `Readable`; `type`: `"remote"`; \} \| \{ `stream`: `ReadStream`; `type`: `"file"`; \}\>
