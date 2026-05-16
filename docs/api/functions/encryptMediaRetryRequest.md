# Function: encryptMediaRetryRequest()

> **encryptMediaRetryRequest**(`key`, `mediaKey`, `meId`): [`BinaryNode`](../type-aliases/BinaryNode.md)

Defined in: [src/Utils/messages-media.ts:908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/messages-media.ts#L908)

Generate a binary node that will request the phone to re-upload the media & return the newly uploaded URL

## Parameters

### key

[`WAMessageKey`](../type-aliases/WAMessageKey.md)

### mediaKey

`Uint8Array`\<`ArrayBufferLike`\> | `Buffer`\<`ArrayBufferLike`\>

### meId

`string`

## Returns

[`BinaryNode`](../type-aliases/BinaryNode.md)
