# Class: WallpaperSettings

Defined in: [WAProto/index.d.ts:13474](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13474)

## Implements

- [`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

## Constructors

### new WallpaperSettings()

> **new WallpaperSettings**(`p`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:13475](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13475)

#### Parameters

##### p?

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

## Properties

### filename?

> `optional` **filename**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13476](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13476)

#### Implementation of

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md).[`filename`](../interfaces/IWallpaperSettings.md#filename)

***

### opacity?

> `optional` **opacity**: `null` \| `number`

Defined in: [WAProto/index.d.ts:13477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13477)

#### Implementation of

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md).[`opacity`](../interfaces/IWallpaperSettings.md#opacity)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13483)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:13478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13478)

#### Parameters

##### properties?

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:13480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13480)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13479)

#### Parameters

##### m

[`IWallpaperSettings`](../interfaces/IWallpaperSettings.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WallpaperSettings`](WallpaperSettings.md)

Defined in: [WAProto/index.d.ts:13481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13481)

#### Parameters

##### d

#### Returns

[`WallpaperSettings`](WallpaperSettings.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13484)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13482)

#### Parameters

##### m

[`WallpaperSettings`](WallpaperSettings.md)

##### o?

`IConversionOptions`

#### Returns

`object`
