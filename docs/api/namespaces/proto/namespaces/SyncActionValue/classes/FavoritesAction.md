# Class: FavoritesAction

Defined in: [WAProto/index.d.ts:11998](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11998)

## Implements

- [`IFavoritesAction`](../interfaces/IFavoritesAction.md)

## Constructors

### new FavoritesAction()

> **new FavoritesAction**(`p`?): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:11999](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11999)

#### Parameters

##### p?

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

#### Returns

[`FavoritesAction`](FavoritesAction.md)

## Properties

### favorites

> **favorites**: [`IFavorite`](../namespaces/FavoritesAction/interfaces/IFavorite.md)[]

Defined in: [WAProto/index.d.ts:12000](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12000)

#### Implementation of

[`IFavoritesAction`](../interfaces/IFavoritesAction.md).[`favorites`](../interfaces/IFavoritesAction.md#favorites)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12006](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12006)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:12001](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12001)

#### Parameters

##### properties?

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

#### Returns

[`FavoritesAction`](FavoritesAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:12003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12003)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`FavoritesAction`](FavoritesAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12002](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12002)

#### Parameters

##### m

[`IFavoritesAction`](../interfaces/IFavoritesAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`FavoritesAction`](FavoritesAction.md)

Defined in: [WAProto/index.d.ts:12004](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12004)

#### Parameters

##### d

#### Returns

[`FavoritesAction`](FavoritesAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12007](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12007)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12005)

#### Parameters

##### m

[`FavoritesAction`](FavoritesAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
