# Class: ProductListInfo

Defined in: [WAProto/index.d.ts:7212](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7212)

## Implements

- [`IProductListInfo`](../interfaces/IProductListInfo.md)

## Constructors

### new ProductListInfo()

> **new ProductListInfo**(`p`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:7213](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7213)

#### Parameters

##### p?

[`IProductListInfo`](../interfaces/IProductListInfo.md)

#### Returns

[`ProductListInfo`](ProductListInfo.md)

## Properties

### businessOwnerJid?

> `optional` **businessOwnerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7216](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7216)

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`businessOwnerJid`](../interfaces/IProductListInfo.md#businessownerjid)

***

### headerImage?

> `optional` **headerImage**: `null` \| [`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:7215](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7215)

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`headerImage`](../interfaces/IProductListInfo.md#headerimage)

***

### productSections

> **productSections**: [`IProductSection`](../interfaces/IProductSection.md)[]

Defined in: [WAProto/index.d.ts:7214](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7214)

#### Implementation of

[`IProductListInfo`](../interfaces/IProductListInfo.md).[`productSections`](../interfaces/IProductListInfo.md#productsections)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7222)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:7217](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7217)

#### Parameters

##### properties?

[`IProductListInfo`](../interfaces/IProductListInfo.md)

#### Returns

[`ProductListInfo`](ProductListInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:7219](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7219)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProductListInfo`](ProductListInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7218](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7218)

#### Parameters

##### m

[`IProductListInfo`](../interfaces/IProductListInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProductListInfo`](ProductListInfo.md)

Defined in: [WAProto/index.d.ts:7220](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7220)

#### Parameters

##### d

#### Returns

[`ProductListInfo`](ProductListInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7223](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7223)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7221](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7221)

#### Parameters

##### m

[`ProductListInfo`](ProductListInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
