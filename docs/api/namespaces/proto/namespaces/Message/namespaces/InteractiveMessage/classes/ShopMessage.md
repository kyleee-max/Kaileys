# Class: ShopMessage

Defined in: [WAProto/index.d.ts:6933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6933)

## Implements

- [`IShopMessage`](../interfaces/IShopMessage.md)

## Constructors

### new ShopMessage()

> **new ShopMessage**(`p`?): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:6934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6934)

#### Parameters

##### p?

[`IShopMessage`](../interfaces/IShopMessage.md)

#### Returns

[`ShopMessage`](ShopMessage.md)

## Properties

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6935)

#### Implementation of

[`IShopMessage`](../interfaces/IShopMessage.md).[`id`](../interfaces/IShopMessage.md#id)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6937](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6937)

#### Implementation of

[`IShopMessage`](../interfaces/IShopMessage.md).[`messageVersion`](../interfaces/IShopMessage.md#messageversion)

***

### surface?

> `optional` **surface**: `null` \| [`Surface`](../namespaces/ShopMessage/enumerations/Surface.md)

Defined in: [WAProto/index.d.ts:6936](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6936)

#### Implementation of

[`IShopMessage`](../interfaces/IShopMessage.md).[`surface`](../interfaces/IShopMessage.md#surface)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6943](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6943)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:6938](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6938)

#### Parameters

##### properties?

[`IShopMessage`](../interfaces/IShopMessage.md)

#### Returns

[`ShopMessage`](ShopMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:6940](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6940)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ShopMessage`](ShopMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6939](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6939)

#### Parameters

##### m

[`IShopMessage`](../interfaces/IShopMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ShopMessage`](ShopMessage.md)

Defined in: [WAProto/index.d.ts:6941](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6941)

#### Parameters

##### d

#### Returns

[`ShopMessage`](ShopMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6944](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6944)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6942](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6942)

#### Parameters

##### m

[`ShopMessage`](ShopMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
