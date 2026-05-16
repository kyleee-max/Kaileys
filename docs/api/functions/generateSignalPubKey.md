# Function: generateSignalPubKey()

> **generateSignalPubKey**(`pubKey`): `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>

Defined in: [src/Utils/crypto.ts:11](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/crypto.ts#L11)

prefix version byte to the pub keys, required for some curve crypto functions

## Parameters

### pubKey

`Uint8Array`\<`ArrayBufferLike`\> | `Buffer`\<`ArrayBufferLike`\>

## Returns

`Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>
