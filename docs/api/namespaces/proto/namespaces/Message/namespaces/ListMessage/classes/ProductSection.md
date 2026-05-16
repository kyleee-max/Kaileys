# Class: ProductSection

Defined in: [WAProto/index.d.ts:7231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7231)

## Implements

- [`IProductSection`](../interfaces/IProductSection.md)

## Constructors

### new ProductSection()

> **new ProductSection**(`p`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:7232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7232)

#### Parameters

##### p?

[`IProductSection`](../interfaces/IProductSection.md)

#### Returns

[`ProductSection`](ProductSection.md)

## Properties

### products

> **products**: [`IProduct`](../interfaces/IProduct.md)[]

Defined in: [WAProto/index.d.ts:7234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7234)

#### Implementation of

[`IProductSection`](../interfaces/IProductSection.md).[`products`](../interfaces/IProductSection.md#products)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7233)

#### Implementation of

[`IProductSection`](../interfaces/IProductSection.md).[`title`](../interfaces/IProductSection.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7240](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7240)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:7235](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7235)

#### Parameters

##### properties?

[`IProductSection`](../interfaces/IProductSection.md)

#### Returns

[`ProductSection`](ProductSection.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:7237](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7237)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProductSection`](ProductSection.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7236](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7236)

#### Parameters

##### m

[`IProductSection`](../interfaces/IProductSection.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProductSection`](ProductSection.md)

Defined in: [WAProto/index.d.ts:7238](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7238)

#### Parameters

##### d

#### Returns

[`ProductSection`](ProductSection.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7241](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7241)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7239](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7239)

#### Parameters

##### m

[`ProductSection`](ProductSection.md)

##### o?

`IConversionOptions`

#### Returns

`object`
