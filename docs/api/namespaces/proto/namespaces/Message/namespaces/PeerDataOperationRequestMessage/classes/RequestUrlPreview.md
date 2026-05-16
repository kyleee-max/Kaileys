# Class: RequestUrlPreview

Defined in: [WAProto/index.d.ts:7907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7907)

## Implements

- [`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

## Constructors

### new RequestUrlPreview()

> **new RequestUrlPreview**(`p`?): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:7908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7908)

#### Parameters

##### p?

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

## Properties

### includeHqThumbnail?

> `optional` **includeHqThumbnail**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7910](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7910)

#### Implementation of

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md).[`includeHqThumbnail`](../interfaces/IRequestUrlPreview.md#includehqthumbnail)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7909](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7909)

#### Implementation of

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md).[`url`](../interfaces/IRequestUrlPreview.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7916](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7916)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:7911](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7911)

#### Parameters

##### properties?

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:7913](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7913)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7912](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7912)

#### Parameters

##### m

[`IRequestUrlPreview`](../interfaces/IRequestUrlPreview.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RequestUrlPreview`](RequestUrlPreview.md)

Defined in: [WAProto/index.d.ts:7914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7914)

#### Parameters

##### d

#### Returns

[`RequestUrlPreview`](RequestUrlPreview.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7917](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7917)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7915](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7915)

#### Parameters

##### m

[`RequestUrlPreview`](RequestUrlPreview.md)

##### o?

`IConversionOptions`

#### Returns

`object`
