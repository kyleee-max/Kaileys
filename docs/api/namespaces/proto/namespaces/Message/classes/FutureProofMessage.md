# Class: FutureProofMessage

Defined in: [WAProto/index.d.ts:6347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6347)

## Implements

- [`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

## Constructors

### new FutureProofMessage()

> **new FutureProofMessage**(`p`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:6348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6348)

#### Parameters

##### p?

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:6349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6349)

#### Implementation of

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md).[`message`](../interfaces/IFutureProofMessage.md#message)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6355](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6355)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:6350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6350)

#### Parameters

##### properties?

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:6352](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6352)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6351)

#### Parameters

##### m

[`IFutureProofMessage`](../interfaces/IFutureProofMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`FutureProofMessage`](FutureProofMessage.md)

Defined in: [WAProto/index.d.ts:6353](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6353)

#### Parameters

##### d

#### Returns

[`FutureProofMessage`](FutureProofMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6356](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6356)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6354](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6354)

#### Parameters

##### m

[`FutureProofMessage`](FutureProofMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
