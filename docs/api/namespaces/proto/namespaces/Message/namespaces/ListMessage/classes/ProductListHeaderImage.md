# Class: ProductListHeaderImage

Defined in: [WAProto/index.d.ts:7193](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7193)

## Implements

- [`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

## Constructors

### new ProductListHeaderImage()

> **new ProductListHeaderImage**(`p`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:7194](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7194)

#### Parameters

##### p?

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

## Properties

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7196)

#### Implementation of

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md).[`jpegThumbnail`](../interfaces/IProductListHeaderImage.md#jpegthumbnail)

***

### productId?

> `optional` **productId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7195)

#### Implementation of

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md).[`productId`](../interfaces/IProductListHeaderImage.md#productid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7202)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:7197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7197)

#### Parameters

##### properties?

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:7199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7199)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7198)

#### Parameters

##### m

[`IProductListHeaderImage`](../interfaces/IProductListHeaderImage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProductListHeaderImage`](ProductListHeaderImage.md)

Defined in: [WAProto/index.d.ts:7200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7200)

#### Parameters

##### d

#### Returns

[`ProductListHeaderImage`](ProductListHeaderImage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7203)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7201)

#### Parameters

##### m

[`ProductListHeaderImage`](ProductListHeaderImage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
