# Class: Body

Defined in: [WAProto/index.d.ts:6986](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6986)

## Implements

- [`IBody`](../interfaces/IBody.md)

## Constructors

### new Body()

> **new Body**(`p`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6987](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6987)

#### Parameters

##### p?

[`IBody`](../interfaces/IBody.md)

#### Returns

[`Body`](Body.md)

## Properties

### format?

> `optional` **format**: `null` \| [`Format`](../namespaces/Body/enumerations/Format.md)

Defined in: [WAProto/index.d.ts:6989](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6989)

#### Implementation of

[`IBody`](../interfaces/IBody.md).[`format`](../interfaces/IBody.md#format)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6988](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6988)

#### Implementation of

[`IBody`](../interfaces/IBody.md).[`text`](../interfaces/IBody.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6995)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6990](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6990)

#### Parameters

##### properties?

[`IBody`](../interfaces/IBody.md)

#### Returns

[`Body`](Body.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6992)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Body`](Body.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6991)

#### Parameters

##### m

[`IBody`](../interfaces/IBody.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6993](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6993)

#### Parameters

##### d

#### Returns

[`Body`](Body.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6996](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6996)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6994)

#### Parameters

##### m

[`Body`](Body.md)

##### o?

`IConversionOptions`

#### Returns

`object`
