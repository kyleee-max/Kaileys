# Class: BotSignatureVerificationMetadata

Defined in: [WAProto/index.d.ts:2118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2118)

## Implements

- [`IBotSignatureVerificationMetadata`](../interfaces/IBotSignatureVerificationMetadata.md)

## Constructors

### new BotSignatureVerificationMetadata()

> **new BotSignatureVerificationMetadata**(`p`?): [`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

Defined in: [WAProto/index.d.ts:2119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2119)

#### Parameters

##### p?

[`IBotSignatureVerificationMetadata`](../interfaces/IBotSignatureVerificationMetadata.md)

#### Returns

[`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

## Properties

### proofs

> **proofs**: [`IBotSignatureVerificationUseCaseProof`](../interfaces/IBotSignatureVerificationUseCaseProof.md)[]

Defined in: [WAProto/index.d.ts:2120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2120)

#### Implementation of

[`IBotSignatureVerificationMetadata`](../interfaces/IBotSignatureVerificationMetadata.md).[`proofs`](../interfaces/IBotSignatureVerificationMetadata.md#proofs)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2126)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

Defined in: [WAProto/index.d.ts:2121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2121)

#### Parameters

##### properties?

[`IBotSignatureVerificationMetadata`](../interfaces/IBotSignatureVerificationMetadata.md)

#### Returns

[`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

Defined in: [WAProto/index.d.ts:2123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2123)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2122](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2122)

#### Parameters

##### m

[`IBotSignatureVerificationMetadata`](../interfaces/IBotSignatureVerificationMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

Defined in: [WAProto/index.d.ts:2124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2124)

#### Parameters

##### d

#### Returns

[`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2127)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2125)

#### Parameters

##### m

[`BotSignatureVerificationMetadata`](BotSignatureVerificationMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
