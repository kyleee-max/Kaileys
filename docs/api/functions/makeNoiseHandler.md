# Function: makeNoiseHandler()

> **makeNoiseHandler**(`__namedParameters`): `object`

Defined in: [src/Utils/noise-handler.ts:52](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/noise-handler.ts#L52)

## Parameters

### \_\_namedParameters

#### keyPair

[`KeyPair`](../type-aliases/KeyPair.md)

#### logger

`ILogger`

#### NOISE_HEADER

`Uint8Array`

#### routingInfo?

`Buffer`\<`ArrayBufferLike`\>

## Returns

`object`

### authenticate()

> **authenticate**: (`data`) => `void`

#### Parameters

##### data

`Uint8Array`

#### Returns

`void`

### decodeFrame()

> **decodeFrame**: (`newData`, `onFrame`) => `Promise`\<`void`\>

#### Parameters

##### newData

`Uint8Array`\<`ArrayBufferLike`\> | `Buffer`\<`ArrayBufferLike`\>

##### onFrame

(`buff`) => `void`

#### Returns

`Promise`\<`void`\>

### decrypt()

> **decrypt**: (`ciphertext`) => `Uint8Array`

#### Parameters

##### ciphertext

`Uint8Array`

#### Returns

`Uint8Array`

### encodeFrame()

> **encodeFrame**: (`data`) => `Buffer`\<`ArrayBuffer`\>

#### Parameters

##### data

`Uint8Array`\<`ArrayBufferLike`\> | `Buffer`\<`ArrayBufferLike`\>

#### Returns

`Buffer`\<`ArrayBuffer`\>

### encrypt()

> **encrypt**: (`plaintext`) => `Uint8Array`

#### Parameters

##### plaintext

`Uint8Array`

#### Returns

`Uint8Array`

### finishInit()

> **finishInit**: () => `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

### mixIntoKey()

> **mixIntoKey**: (`data`) => `void`

#### Parameters

##### data

`Uint8Array`

#### Returns

`void`

### processHandshake()

> **processHandshake**: (`__namedParameters`, `noiseKey`) => `Uint8Array`\<`ArrayBufferLike`\>

#### Parameters

##### \_\_namedParameters

[`HandshakeMessage`](../namespaces/proto/classes/HandshakeMessage.md)

##### noiseKey

[`KeyPair`](../type-aliases/KeyPair.md)

#### Returns

`Uint8Array`\<`ArrayBufferLike`\>
