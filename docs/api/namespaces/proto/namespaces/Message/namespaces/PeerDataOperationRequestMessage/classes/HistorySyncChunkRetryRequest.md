# Class: HistorySyncChunkRetryRequest

Defined in: [WAProto/index.d.ts:7829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7829)

## Implements

- [`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md)

## Constructors

### new HistorySyncChunkRetryRequest()

> **new HistorySyncChunkRetryRequest**(`p`?): [`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

Defined in: [WAProto/index.d.ts:7830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7830)

#### Parameters

##### p?

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md)

#### Returns

[`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

## Properties

### chunkNotificationId?

> `optional` **chunkNotificationId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7833)

#### Implementation of

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md).[`chunkNotificationId`](../interfaces/IHistorySyncChunkRetryRequest.md#chunknotificationid)

***

### chunkOrder?

> `optional` **chunkOrder**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7832)

#### Implementation of

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md).[`chunkOrder`](../interfaces/IHistorySyncChunkRetryRequest.md#chunkorder)

***

### regenerateChunk?

> `optional` **regenerateChunk**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7834)

#### Implementation of

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md).[`regenerateChunk`](../interfaces/IHistorySyncChunkRetryRequest.md#regeneratechunk)

***

### syncType?

> `optional` **syncType**: `null` \| [`HistorySyncType`](../../../enumerations/HistorySyncType.md)

Defined in: [WAProto/index.d.ts:7831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7831)

#### Implementation of

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md).[`syncType`](../interfaces/IHistorySyncChunkRetryRequest.md#synctype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7840](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7840)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

Defined in: [WAProto/index.d.ts:7835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7835)

#### Parameters

##### properties?

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md)

#### Returns

[`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

Defined in: [WAProto/index.d.ts:7837](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7837)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7836](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7836)

#### Parameters

##### m

[`IHistorySyncChunkRetryRequest`](../interfaces/IHistorySyncChunkRetryRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

Defined in: [WAProto/index.d.ts:7838](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7838)

#### Parameters

##### d

#### Returns

[`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7841](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7841)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7839](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7839)

#### Parameters

##### m

[`HistorySyncChunkRetryRequest`](HistorySyncChunkRetryRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
