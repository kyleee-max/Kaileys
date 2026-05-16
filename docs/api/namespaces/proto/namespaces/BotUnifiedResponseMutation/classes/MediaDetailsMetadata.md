# Class: MediaDetailsMetadata

Defined in: [WAProto/index.d.ts:2266](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2266)

## Implements

- [`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md)

## Constructors

### new MediaDetailsMetadata()

> **new MediaDetailsMetadata**(`p`?): [`MediaDetailsMetadata`](MediaDetailsMetadata.md)

Defined in: [WAProto/index.d.ts:2267](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2267)

#### Parameters

##### p?

[`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md)

#### Returns

[`MediaDetailsMetadata`](MediaDetailsMetadata.md)

## Properties

### highResMedia?

> `optional` **highResMedia**: `null` \| [`IBotMediaMetadata`](../../../interfaces/IBotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:2269](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2269)

#### Implementation of

[`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md).[`highResMedia`](../interfaces/IMediaDetailsMetadata.md#highresmedia)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2268](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2268)

#### Implementation of

[`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md).[`id`](../interfaces/IMediaDetailsMetadata.md#id)

***

### previewMedia?

> `optional` **previewMedia**: `null` \| [`IBotMediaMetadata`](../../../interfaces/IBotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:2270](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2270)

#### Implementation of

[`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md).[`previewMedia`](../interfaces/IMediaDetailsMetadata.md#previewmedia)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2276](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2276)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MediaDetailsMetadata`](MediaDetailsMetadata.md)

Defined in: [WAProto/index.d.ts:2271](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2271)

#### Parameters

##### properties?

[`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md)

#### Returns

[`MediaDetailsMetadata`](MediaDetailsMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MediaDetailsMetadata`](MediaDetailsMetadata.md)

Defined in: [WAProto/index.d.ts:2273](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2273)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MediaDetailsMetadata`](MediaDetailsMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2272)

#### Parameters

##### m

[`IMediaDetailsMetadata`](../interfaces/IMediaDetailsMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MediaDetailsMetadata`](MediaDetailsMetadata.md)

Defined in: [WAProto/index.d.ts:2274](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2274)

#### Parameters

##### d

#### Returns

[`MediaDetailsMetadata`](MediaDetailsMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2277](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2277)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2275](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2275)

#### Parameters

##### m

[`MediaDetailsMetadata`](MediaDetailsMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
