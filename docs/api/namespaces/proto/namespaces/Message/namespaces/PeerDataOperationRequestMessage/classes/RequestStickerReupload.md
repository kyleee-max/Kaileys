# Class: RequestStickerReupload

Defined in: [WAProto/index.d.ts:7890](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7890)

## Implements

- [`IRequestStickerReupload`](../interfaces/IRequestStickerReupload.md)

## Constructors

### new RequestStickerReupload()

> **new RequestStickerReupload**(`p`?): [`RequestStickerReupload`](RequestStickerReupload.md)

Defined in: [WAProto/index.d.ts:7891](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7891)

#### Parameters

##### p?

[`IRequestStickerReupload`](../interfaces/IRequestStickerReupload.md)

#### Returns

[`RequestStickerReupload`](RequestStickerReupload.md)

## Properties

### fileSha256?

> `optional` **fileSha256**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7892](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7892)

#### Implementation of

[`IRequestStickerReupload`](../interfaces/IRequestStickerReupload.md).[`fileSha256`](../interfaces/IRequestStickerReupload.md#filesha256)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7898)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RequestStickerReupload`](RequestStickerReupload.md)

Defined in: [WAProto/index.d.ts:7893](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7893)

#### Parameters

##### properties?

[`IRequestStickerReupload`](../interfaces/IRequestStickerReupload.md)

#### Returns

[`RequestStickerReupload`](RequestStickerReupload.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RequestStickerReupload`](RequestStickerReupload.md)

Defined in: [WAProto/index.d.ts:7895](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7895)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RequestStickerReupload`](RequestStickerReupload.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7894](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7894)

#### Parameters

##### m

[`IRequestStickerReupload`](../interfaces/IRequestStickerReupload.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RequestStickerReupload`](RequestStickerReupload.md)

Defined in: [WAProto/index.d.ts:7896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7896)

#### Parameters

##### d

#### Returns

[`RequestStickerReupload`](RequestStickerReupload.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7899)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7897)

#### Parameters

##### m

[`RequestStickerReupload`](RequestStickerReupload.md)

##### o?

`IConversionOptions`

#### Returns

`object`
