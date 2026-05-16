# Class: MediaRetryNotification

Defined in: [WAProto/index.d.ts:5136](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5136)

## Implements

- [`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

## Constructors

### new MediaRetryNotification()

> **new MediaRetryNotification**(`p`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:5137](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5137)

#### Parameters

##### p?

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5139](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5139)

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`directPath`](../interfaces/IMediaRetryNotification.md#directpath)

***

### messageSecret?

> `optional` **messageSecret**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5141](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5141)

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`messageSecret`](../interfaces/IMediaRetryNotification.md#messagesecret)

***

### result?

> `optional` **result**: `null` \| [`ResultType`](../namespaces/MediaRetryNotification/enumerations/ResultType.md)

Defined in: [WAProto/index.d.ts:5140](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5140)

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`result`](../interfaces/IMediaRetryNotification.md#result)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5138](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5138)

#### Implementation of

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md).[`stanzaId`](../interfaces/IMediaRetryNotification.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5147)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:5142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5142)

#### Parameters

##### properties?

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:5144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5144)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5143](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5143)

#### Parameters

##### m

[`IMediaRetryNotification`](../interfaces/IMediaRetryNotification.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MediaRetryNotification`](MediaRetryNotification.md)

Defined in: [WAProto/index.d.ts:5145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5145)

#### Parameters

##### d

#### Returns

[`MediaRetryNotification`](MediaRetryNotification.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5148)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5146)

#### Parameters

##### m

[`MediaRetryNotification`](MediaRetryNotification.md)

##### o?

`IConversionOptions`

#### Returns

`object`
