# Class: CatalogSnapshot

Defined in: [WAProto/index.d.ts:8503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8503)

## Implements

- [`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

## Constructors

### new CatalogSnapshot()

> **new CatalogSnapshot**(`p`?): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:8504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8504)

#### Parameters

##### p?

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

## Properties

### catalogImage?

> `optional` **catalogImage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:8505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8505)

#### Implementation of

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md).[`catalogImage`](../interfaces/ICatalogSnapshot.md#catalogimage)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8507](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8507)

#### Implementation of

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md).[`description`](../interfaces/ICatalogSnapshot.md#description)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8506)

#### Implementation of

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md).[`title`](../interfaces/ICatalogSnapshot.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8513)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:8508](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8508)

#### Parameters

##### properties?

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:8510](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8510)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8509](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8509)

#### Parameters

##### m

[`ICatalogSnapshot`](../interfaces/ICatalogSnapshot.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CatalogSnapshot`](CatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:8511](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8511)

#### Parameters

##### d

#### Returns

[`CatalogSnapshot`](CatalogSnapshot.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8514](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8514)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8512](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8512)

#### Parameters

##### m

[`CatalogSnapshot`](CatalogSnapshot.md)

##### o?

`IConversionOptions`

#### Returns

`object`
