# Class: HistorySyncChunkRetryResponse

Defined in: [WAProto/index.d.ts:8069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8069)

## Implements

- [`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md)

## Constructors

### new HistorySyncChunkRetryResponse()

> **new HistorySyncChunkRetryResponse**(`p`?): [`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

Defined in: [WAProto/index.d.ts:8070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8070)

#### Parameters

##### p?

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md)

#### Returns

[`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

## Properties

### canRecover?

> `optional` **canRecover**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:8075](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8075)

#### Implementation of

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md).[`canRecover`](../interfaces/IHistorySyncChunkRetryResponse.md#canrecover)

***

### chunkOrder?

> `optional` **chunkOrder**: `null` \| `number`

Defined in: [WAProto/index.d.ts:8072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8072)

#### Implementation of

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md).[`chunkOrder`](../interfaces/IHistorySyncChunkRetryResponse.md#chunkorder)

***

### requestId?

> `optional` **requestId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8073](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8073)

#### Implementation of

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md).[`requestId`](../interfaces/IHistorySyncChunkRetryResponse.md#requestid)

***

### responseCode?

> `optional` **responseCode**: `null` \| [`HistorySyncChunkRetryResponseCode`](../enumerations/HistorySyncChunkRetryResponseCode.md)

Defined in: [WAProto/index.d.ts:8074](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8074)

#### Implementation of

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md).[`responseCode`](../interfaces/IHistorySyncChunkRetryResponse.md#responsecode)

***

### syncType?

> `optional` **syncType**: `null` \| [`HistorySyncType`](../../../../../enumerations/HistorySyncType.md)

Defined in: [WAProto/index.d.ts:8071](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8071)

#### Implementation of

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md).[`syncType`](../interfaces/IHistorySyncChunkRetryResponse.md#synctype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8081](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8081)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

Defined in: [WAProto/index.d.ts:8076](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8076)

#### Parameters

##### properties?

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md)

#### Returns

[`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

Defined in: [WAProto/index.d.ts:8078](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8078)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8077](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8077)

#### Parameters

##### m

[`IHistorySyncChunkRetryResponse`](../interfaces/IHistorySyncChunkRetryResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

Defined in: [WAProto/index.d.ts:8079](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8079)

#### Parameters

##### d

#### Returns

[`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8082](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8082)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8080](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8080)

#### Parameters

##### m

[`HistorySyncChunkRetryResponse`](HistorySyncChunkRetryResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
