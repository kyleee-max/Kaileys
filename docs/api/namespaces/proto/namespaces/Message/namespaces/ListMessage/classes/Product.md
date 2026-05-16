# Class: Product

Defined in: [WAProto/index.d.ts:7176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7176)

## Implements

- [`IProduct`](../interfaces/IProduct.md)

## Constructors

### new Product()

> **new Product**(`p`?): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:7177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7177)

#### Parameters

##### p?

[`IProduct`](../interfaces/IProduct.md)

#### Returns

[`Product`](Product.md)

## Properties

### productId?

> `optional` **productId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7178)

#### Implementation of

[`IProduct`](../interfaces/IProduct.md).[`productId`](../interfaces/IProduct.md#productid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7184](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7184)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:7179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7179)

#### Parameters

##### properties?

[`IProduct`](../interfaces/IProduct.md)

#### Returns

[`Product`](Product.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:7181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7181)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Product`](Product.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7180)

#### Parameters

##### m

[`IProduct`](../interfaces/IProduct.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Product`](Product.md)

Defined in: [WAProto/index.d.ts:7182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7182)

#### Parameters

##### d

#### Returns

[`Product`](Product.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7185](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7185)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7183](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7183)

#### Parameters

##### m

[`Product`](Product.md)

##### o?

`IConversionOptions`

#### Returns

`object`
