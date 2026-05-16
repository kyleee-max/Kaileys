# Class: MediaData

Defined in: [WAProto/index.d.ts:5097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5097)

## Implements

- [`IMediaData`](../interfaces/IMediaData.md)

## Constructors

### new MediaData()

> **new MediaData**(`p`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:5098](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5098)

#### Parameters

##### p?

[`IMediaData`](../interfaces/IMediaData.md)

#### Returns

[`MediaData`](MediaData.md)

## Properties

### localPath?

> `optional` **localPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5099](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5099)

#### Implementation of

[`IMediaData`](../interfaces/IMediaData.md).[`localPath`](../interfaces/IMediaData.md#localpath)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5105](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5105)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:5100](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5100)

#### Parameters

##### properties?

[`IMediaData`](../interfaces/IMediaData.md)

#### Returns

[`MediaData`](MediaData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MediaData`](MediaData.md)

Defined in: [WAProto/index.d.ts:5102](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5102)

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

Defined in: [WAProto/index.d.ts:5101](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5101)

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

Defined in: [WAProto/index.d.ts:5103](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5103)

#### Parameters

##### d

#### Returns

[`MediaData`](MediaData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5106](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5106)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5104](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5104)

#### Parameters

##### m

[`MediaData`](MediaData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
