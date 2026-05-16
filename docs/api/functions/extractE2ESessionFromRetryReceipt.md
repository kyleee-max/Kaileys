# Function: extractE2ESessionFromRetryReceipt()

> **extractE2ESessionFromRetryReceipt**(`receipt`): `null` \| \{ `identityKey`: `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>; `preKey`: `undefined` \| \{ `keyId`: `number`; `publicKey`: `Uint8Array`; \}; `registrationId`: `number`; `signedPreKey`: \{ `keyId`: `number`; `publicKey`: `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>; `signature`: `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>; \}; \}

Defined in: [src/Utils/signal.ts:92](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/signal.ts#L92)

## Parameters

### receipt

[`BinaryNode`](../type-aliases/BinaryNode.md)

## Returns

`null` \| \{ `identityKey`: `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>; `preKey`: `undefined` \| \{ `keyId`: `number`; `publicKey`: `Uint8Array`; \}; `registrationId`: `number`; `signedPreKey`: \{ `keyId`: `number`; `publicKey`: `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>; `signature`: `Uint8Array`\<`ArrayBufferLike`\> \| `Buffer`\<`ArrayBufferLike`\>; \}; \}
