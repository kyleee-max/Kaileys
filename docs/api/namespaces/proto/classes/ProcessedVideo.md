# Class: ProcessedVideo

Defined in: [WAProto/index.d.ts:10540](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10540)

## Implements

- [`IProcessedVideo`](../interfaces/IProcessedVideo.md)

## Constructors

### new ProcessedVideo()

> **new ProcessedVideo**(`p`?): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:10541](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10541)

#### Parameters

##### p?

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

## Properties

### bitrate?

> `optional` **bitrate**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10547](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10547)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`bitrate`](../interfaces/IProcessedVideo.md#bitrate)

***

### capabilities

> **capabilities**: `string`[]

Defined in: [WAProto/index.d.ts:10549](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10549)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`capabilities`](../interfaces/IProcessedVideo.md#capabilities)

***

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10542](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10542)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`directPath`](../interfaces/IProcessedVideo.md#directpath)

***

### fileLength?

> `optional` **fileLength**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10546](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10546)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`fileLength`](../interfaces/IProcessedVideo.md#filelength)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10543](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10543)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`fileSha256`](../interfaces/IProcessedVideo.md#filesha256)

***

### height?

> `optional` **height**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10544](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10544)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`height`](../interfaces/IProcessedVideo.md#height)

***

### quality?

> `optional` **quality**: `null` \| [`VideoQuality`](../namespaces/ProcessedVideo/enumerations/VideoQuality.md)

Defined in: [WAProto/index.d.ts:10548](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10548)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`quality`](../interfaces/IProcessedVideo.md#quality)

***

### width?

> `optional` **width**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10545](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10545)

#### Implementation of

[`IProcessedVideo`](../interfaces/IProcessedVideo.md).[`width`](../interfaces/IProcessedVideo.md#width)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10555](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10555)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:10550](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10550)

#### Parameters

##### properties?

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:10552](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10552)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10551](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10551)

#### Parameters

##### m

[`IProcessedVideo`](../interfaces/IProcessedVideo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProcessedVideo`](ProcessedVideo.md)

Defined in: [WAProto/index.d.ts:10553](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10553)

#### Parameters

##### d

#### Returns

[`ProcessedVideo`](ProcessedVideo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10556](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10556)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10554](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10554)

#### Parameters

##### m

[`ProcessedVideo`](ProcessedVideo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
