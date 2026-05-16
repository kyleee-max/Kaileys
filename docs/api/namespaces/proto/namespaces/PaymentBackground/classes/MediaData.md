# Class: MediaData

Defined in: [WAProto/index.d.ts:10172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10172)

## Implements

- [`IMediaData`](../interfaces/IMediaData.md)

## Constructors

### new MediaData()

> **new MediaData**(`p`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:10173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10173)

#### Parameters

##### p?

[`IMediaData`](../interfaces/IMediaData.md)

#### Returns

[`MediaData`](MediaData.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10178)

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`directPath`](../interfaces/IMediaData.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10177)

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`fileEncSha256`](../interfaces/IMediaData.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10176)

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`fileSha256`](../interfaces/IMediaData.md#filesha256)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10174)

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`mediaKey`](../interfaces/IMediaData.md#mediakey)

***

### mediaKeyTimestamp?

> `optional` **mediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10175)

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`mediaKeyTimestamp`](../interfaces/IMediaData.md#mediakeytimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10184](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10184)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:10179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10179)

#### Parameters

##### properties?

[`IMediaData`](../interfaces/IMediaData.md)

#### Returns

[`MediaData`](MediaData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:10181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10181)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MediaData`](MediaData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10180)

#### Parameters

##### m

[`IMediaData`](../interfaces/IMediaData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:10182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10182)

#### Parameters

##### d

#### Returns

[`MediaData`](MediaData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10185](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10185)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10183](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10183)

#### Parameters

##### m

[`MediaData`](MediaData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
