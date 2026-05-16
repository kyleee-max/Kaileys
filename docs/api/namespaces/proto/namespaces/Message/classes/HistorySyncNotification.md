# Class: HistorySyncNotification

Defined in: [WAProto/index.d.ts:6592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6592)

## Implements

- [`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

## Constructors

### new HistorySyncNotification()

> **new HistorySyncNotification**(`p`?): [`HistorySyncNotification`](HistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:6593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6593)

#### Parameters

##### p?

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

#### Returns

[`HistorySyncNotification`](HistorySyncNotification.md)

## Properties

### chunkOrder?

> `optional` **chunkOrder**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6600)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`chunkOrder`](../interfaces/IHistorySyncNotification.md#chunkorder)

***

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6598)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`directPath`](../interfaces/IHistorySyncNotification.md#directpath)

***

### encHandle?

> `optional` **encHandle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6607](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6607)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`encHandle`](../interfaces/IHistorySyncNotification.md#enchandle)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6597)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`fileEncSha256`](../interfaces/IHistorySyncNotification.md#fileencsha256)

***

### fileLength?

> `optional` **fileLength**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6595)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`fileLength`](../interfaces/IHistorySyncNotification.md#filelength)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6594)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`fileSha256`](../interfaces/IHistorySyncNotification.md#filesha256)

***

### fullHistorySyncOnDemandRequestMetadata?

> `optional` **fullHistorySyncOnDemandRequestMetadata**: `null` \| [`IFullHistorySyncOnDemandRequestMetadata`](../interfaces/IFullHistorySyncOnDemandRequestMetadata.md)

Defined in: [WAProto/index.d.ts:6606](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6606)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`fullHistorySyncOnDemandRequestMetadata`](../interfaces/IHistorySyncNotification.md#fullhistorysyncondemandrequestmetadata)

***

### initialHistBootstrapInlinePayload?

> `optional` **initialHistBootstrapInlinePayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6604](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6604)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`initialHistBootstrapInlinePayload`](../interfaces/IHistorySyncNotification.md#initialhistbootstrapinlinepayload)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6596)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`mediaKey`](../interfaces/IHistorySyncNotification.md#mediakey)

***

### messageAccessStatus?

> `optional` **messageAccessStatus**: `null` \| [`IHistorySyncMessageAccessStatus`](../interfaces/IHistorySyncMessageAccessStatus.md)

Defined in: [WAProto/index.d.ts:6608](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6608)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`messageAccessStatus`](../interfaces/IHistorySyncNotification.md#messageaccessstatus)

***

### oldestMsgInChunkTimestampSec?

> `optional` **oldestMsgInChunkTimestampSec**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6603](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6603)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`oldestMsgInChunkTimestampSec`](../interfaces/IHistorySyncNotification.md#oldestmsginchunktimestampsec)

***

### originalMessageId?

> `optional` **originalMessageId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6601](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6601)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`originalMessageId`](../interfaces/IHistorySyncNotification.md#originalmessageid)

***

### peerDataRequestSessionId?

> `optional` **peerDataRequestSessionId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6605](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6605)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`peerDataRequestSessionId`](../interfaces/IHistorySyncNotification.md#peerdatarequestsessionid)

***

### progress?

> `optional` **progress**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6602](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6602)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`progress`](../interfaces/IHistorySyncNotification.md#progress)

***

### syncType?

> `optional` **syncType**: `null` \| [`HistorySyncType`](../enumerations/HistorySyncType.md)

Defined in: [WAProto/index.d.ts:6599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6599)

#### Implementation of

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md).[`syncType`](../interfaces/IHistorySyncNotification.md#synctype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6614](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6614)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HistorySyncNotification`](HistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:6609](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6609)

#### Parameters

##### properties?

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

#### Returns

[`HistorySyncNotification`](HistorySyncNotification.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HistorySyncNotification`](HistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:6611](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6611)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HistorySyncNotification`](HistorySyncNotification.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6610](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6610)

#### Parameters

##### m

[`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HistorySyncNotification`](HistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:6612](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6612)

#### Parameters

##### d

#### Returns

[`HistorySyncNotification`](HistorySyncNotification.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6615](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6615)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6613](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6613)

#### Parameters

##### m

[`HistorySyncNotification`](HistorySyncNotification.md)

##### o?

`IConversionOptions`

#### Returns

`object`
