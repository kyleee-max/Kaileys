# Class: AlbumMessage

Defined in: [WAProto/index.d.ts:5397](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5397)

## Implements

- [`IAlbumMessage`](../interfaces/IAlbumMessage.md)

## Constructors

### new AlbumMessage()

> **new AlbumMessage**(`p`?): [`AlbumMessage`](AlbumMessage.md)

Defined in: [WAProto/index.d.ts:5398](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5398)

#### Parameters

##### p?

[`IAlbumMessage`](../interfaces/IAlbumMessage.md)

#### Returns

[`AlbumMessage`](AlbumMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:5401](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5401)

#### Implementation of

[`IAlbumMessage`](../interfaces/IAlbumMessage.md).[`contextInfo`](../interfaces/IAlbumMessage.md#contextinfo)

***

### expectedImageCount?

> `optional` **expectedImageCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5399](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5399)

#### Implementation of

[`IAlbumMessage`](../interfaces/IAlbumMessage.md).[`expectedImageCount`](../interfaces/IAlbumMessage.md#expectedimagecount)

***

### expectedVideoCount?

> `optional` **expectedVideoCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5400](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5400)

#### Implementation of

[`IAlbumMessage`](../interfaces/IAlbumMessage.md).[`expectedVideoCount`](../interfaces/IAlbumMessage.md#expectedvideocount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5407](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5407)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AlbumMessage`](AlbumMessage.md)

Defined in: [WAProto/index.d.ts:5402](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5402)

#### Parameters

##### properties?

[`IAlbumMessage`](../interfaces/IAlbumMessage.md)

#### Returns

[`AlbumMessage`](AlbumMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AlbumMessage`](AlbumMessage.md)

Defined in: [WAProto/index.d.ts:5404](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5404)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AlbumMessage`](AlbumMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5403](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5403)

#### Parameters

##### m

[`IAlbumMessage`](../interfaces/IAlbumMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AlbumMessage`](AlbumMessage.md)

Defined in: [WAProto/index.d.ts:5405](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5405)

#### Parameters

##### d

#### Returns

[`AlbumMessage`](AlbumMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5408](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5408)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5406](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5406)

#### Parameters

##### m

[`AlbumMessage`](AlbumMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
