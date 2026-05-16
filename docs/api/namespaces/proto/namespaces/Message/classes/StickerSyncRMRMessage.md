# Class: StickerSyncRMRMessage

Defined in: [WAProto/index.d.ts:9144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9144)

## Implements

- [`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

## Constructors

### new StickerSyncRMRMessage()

> **new StickerSyncRMRMessage**(`p`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:9145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9145)

#### Parameters

##### p?

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

## Properties

### filehash

> **filehash**: `string`[]

Defined in: [WAProto/index.d.ts:9146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9146)

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`filehash`](../interfaces/IStickerSyncRMRMessage.md#filehash)

***

### requestTimestamp?

> `optional` **requestTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9148)

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`requestTimestamp`](../interfaces/IStickerSyncRMRMessage.md#requesttimestamp)

***

### rmrSource?

> `optional` **rmrSource**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9147)

#### Implementation of

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md).[`rmrSource`](../interfaces/IStickerSyncRMRMessage.md#rmrsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9154](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9154)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:9149](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9149)

#### Parameters

##### properties?

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:9151](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9151)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9150](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9150)

#### Parameters

##### m

[`IStickerSyncRMRMessage`](../interfaces/IStickerSyncRMRMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

Defined in: [WAProto/index.d.ts:9152](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9152)

#### Parameters

##### d

#### Returns

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9155](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9155)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9153](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9153)

#### Parameters

##### m

[`StickerSyncRMRMessage`](StickerSyncRMRMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
