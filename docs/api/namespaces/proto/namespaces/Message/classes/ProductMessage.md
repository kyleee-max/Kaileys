# Class: ProductMessage

Defined in: [WAProto/index.d.ts:8478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8478)

## Implements

- [`IProductMessage`](../interfaces/IProductMessage.md)

## Constructors

### new ProductMessage()

> **new ProductMessage**(`p`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:8479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8479)

#### Parameters

##### p?

[`IProductMessage`](../interfaces/IProductMessage.md)

#### Returns

[`ProductMessage`](ProductMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8483)

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`body`](../interfaces/IProductMessage.md#body)

***

### businessOwnerJid?

> `optional` **businessOwnerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8481)

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`businessOwnerJid`](../interfaces/IProductMessage.md#businessownerjid)

***

### catalog?

> `optional` **catalog**: `null` \| [`ICatalogSnapshot`](../namespaces/ProductMessage/interfaces/ICatalogSnapshot.md)

Defined in: [WAProto/index.d.ts:8482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8482)

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`catalog`](../interfaces/IProductMessage.md#catalog)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:8485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8485)

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`contextInfo`](../interfaces/IProductMessage.md#contextinfo)

***

### footer?

> `optional` **footer**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8484)

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`footer`](../interfaces/IProductMessage.md#footer)

***

### product?

> `optional` **product**: `null` \| [`IProductSnapshot`](../namespaces/ProductMessage/interfaces/IProductSnapshot.md)

Defined in: [WAProto/index.d.ts:8480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8480)

#### Implementation of

[`IProductMessage`](../interfaces/IProductMessage.md).[`product`](../interfaces/IProductMessage.md#product)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8491](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8491)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:8486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8486)

#### Parameters

##### properties?

[`IProductMessage`](../interfaces/IProductMessage.md)

#### Returns

[`ProductMessage`](ProductMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:8488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8488)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProductMessage`](ProductMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8487)

#### Parameters

##### m

[`IProductMessage`](../interfaces/IProductMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProductMessage`](ProductMessage.md)

Defined in: [WAProto/index.d.ts:8489](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8489)

#### Parameters

##### d

#### Returns

[`ProductMessage`](ProductMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8492](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8492)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8490](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8490)

#### Parameters

##### m

[`ProductMessage`](ProductMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
