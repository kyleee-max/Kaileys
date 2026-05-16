# Class: BotSignatureVerificationUseCaseProof

Defined in: [WAProto/index.d.ts:2137](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2137)

## Implements

- [`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md)

## Constructors

### new BotSignatureVerificationUseCaseProof()

> **new BotSignatureVerificationUseCaseProof**(`p`?): [`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

Defined in: [WAProto/index.d.ts:2138](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2138)

#### Parameters

##### p?

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md)

#### Returns

[`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

## Properties

### certificateChain

> **certificateChain**: `Uint8Array`\<`ArrayBufferLike`\>[]

Defined in: [WAProto/index.d.ts:2142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2142)

#### Implementation of

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md).[`certificateChain`](../interfaces/IBotSignatureVerificationUseCaseProof.md#certificatechain)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2141](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2141)

#### Implementation of

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md).[`signature`](../interfaces/IBotSignatureVerificationUseCaseProof.md#signature)

***

### useCase?

> `optional` **useCase**: `null` \| [`BotSignatureUseCase`](../namespaces/BotSignatureVerificationUseCaseProof/enumerations/BotSignatureUseCase.md)

Defined in: [WAProto/index.d.ts:2140](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2140)

#### Implementation of

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md).[`useCase`](../interfaces/IBotSignatureVerificationUseCaseProof.md#usecase)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2139](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2139)

#### Implementation of

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md).[`version`](../interfaces/IBotSignatureVerificationUseCaseProof.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2148)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

Defined in: [WAProto/index.d.ts:2143](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2143)

#### Parameters

##### properties?

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md)

#### Returns

[`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

Defined in: [WAProto/index.d.ts:2145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2145)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2144)

#### Parameters

##### m

[`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

Defined in: [WAProto/index.d.ts:2146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2146)

#### Parameters

##### d

#### Returns

[`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2149](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2149)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2147)

#### Parameters

##### m

[`BotSignatureVerificationUseCaseProof`](BotSignatureVerificationUseCaseProof.md)

##### o?

`IConversionOptions`

#### Returns

`object`
