# Class: ParticipantInfo

Defined in: [WAProto/index.d.ts:2370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2370)

## Implements

- [`IParticipantInfo`](../interfaces/IParticipantInfo.md)

## Constructors

### new ParticipantInfo()

> **new ParticipantInfo**(`p`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:2371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2371)

#### Parameters

##### p?

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

## Properties

### callResult?

> `optional` **callResult**: `null` \| [`CallResult`](../enumerations/CallResult.md)

Defined in: [WAProto/index.d.ts:2373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2373)

#### Implementation of

[`IParticipantInfo`](../interfaces/IParticipantInfo.md).[`callResult`](../interfaces/IParticipantInfo.md#callresult)

***

### userJid?

> `optional` **userJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2372)

#### Implementation of

[`IParticipantInfo`](../interfaces/IParticipantInfo.md).[`userJid`](../interfaces/IParticipantInfo.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2379](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2379)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:2374](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2374)

#### Parameters

##### properties?

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:2376](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2376)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2375](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2375)

#### Parameters

##### m

[`IParticipantInfo`](../interfaces/IParticipantInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ParticipantInfo`](ParticipantInfo.md)

Defined in: [WAProto/index.d.ts:2377](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2377)

#### Parameters

##### d

#### Returns

[`ParticipantInfo`](ParticipantInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2380](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2380)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2378](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2378)

#### Parameters

##### m

[`ParticipantInfo`](ParticipantInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
