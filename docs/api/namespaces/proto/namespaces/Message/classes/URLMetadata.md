# Class: URLMetadata

Defined in: [WAProto/index.d.ts:9282](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9282)

## Implements

- [`IURLMetadata`](../interfaces/IURLMetadata.md)

## Constructors

### new URLMetadata()

> **new URLMetadata**(`p`?): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:9283](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9283)

#### Parameters

##### p?

[`IURLMetadata`](../interfaces/IURLMetadata.md)

#### Returns

[`URLMetadata`](URLMetadata.md)

## Properties

### fbExperimentId?

> `optional` **fbExperimentId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9284](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9284)

#### Implementation of

[`IURLMetadata`](../interfaces/IURLMetadata.md).[`fbExperimentId`](../interfaces/IURLMetadata.md#fbexperimentid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9290](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9290)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:9285](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9285)

#### Parameters

##### properties?

[`IURLMetadata`](../interfaces/IURLMetadata.md)

#### Returns

[`URLMetadata`](URLMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:9287](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9287)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`URLMetadata`](URLMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9286](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9286)

#### Parameters

##### m

[`IURLMetadata`](../interfaces/IURLMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`URLMetadata`](URLMetadata.md)

Defined in: [WAProto/index.d.ts:9288](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9288)

#### Parameters

##### d

#### Returns

[`URLMetadata`](URLMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9291)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9289](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9289)

#### Parameters

##### m

[`URLMetadata`](URLMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
