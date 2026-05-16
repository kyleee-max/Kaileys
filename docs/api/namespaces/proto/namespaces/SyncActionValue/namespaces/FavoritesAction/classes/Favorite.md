# Class: Favorite

Defined in: [WAProto/index.d.ts:12016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12016)

## Implements

- [`IFavorite`](../interfaces/IFavorite.md)

## Constructors

### new Favorite()

> **new Favorite**(`p`?): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:12017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12017)

#### Parameters

##### p?

[`IFavorite`](../interfaces/IFavorite.md)

#### Returns

[`Favorite`](Favorite.md)

## Properties

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12018)

#### Implementation of

[`IFavorite`](../interfaces/IFavorite.md).[`id`](../interfaces/IFavorite.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12024)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:12019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12019)

#### Parameters

##### properties?

[`IFavorite`](../interfaces/IFavorite.md)

#### Returns

[`Favorite`](Favorite.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:12021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12021)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Favorite`](Favorite.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12020)

#### Parameters

##### m

[`IFavorite`](../interfaces/IFavorite.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Favorite`](Favorite.md)

Defined in: [WAProto/index.d.ts:12022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12022)

#### Parameters

##### d

#### Returns

[`Favorite`](Favorite.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12025)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12023)

#### Parameters

##### m

[`Favorite`](Favorite.md)

##### o?

`IConversionOptions`

#### Returns

`object`
