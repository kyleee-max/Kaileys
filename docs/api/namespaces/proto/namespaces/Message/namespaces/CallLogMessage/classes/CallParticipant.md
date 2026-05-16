# Class: CallParticipant

Defined in: [WAProto/index.d.ts:5832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5832)

## Implements

- [`ICallParticipant`](../interfaces/ICallParticipant.md)

## Constructors

### new CallParticipant()

> **new CallParticipant**(`p`?): [`CallParticipant`](CallParticipant.md)

Defined in: [WAProto/index.d.ts:5833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5833)

#### Parameters

##### p?

[`ICallParticipant`](../interfaces/ICallParticipant.md)

#### Returns

[`CallParticipant`](CallParticipant.md)

## Properties

### callOutcome?

> `optional` **callOutcome**: `null` \| [`CallOutcome`](../enumerations/CallOutcome.md)

Defined in: [WAProto/index.d.ts:5835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5835)

#### Implementation of

[`ICallParticipant`](../interfaces/ICallParticipant.md).[`callOutcome`](../interfaces/ICallParticipant.md#calloutcome)

***

### jid?

> `optional` **jid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5834)

#### Implementation of

[`ICallParticipant`](../interfaces/ICallParticipant.md).[`jid`](../interfaces/ICallParticipant.md#jid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5841](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5841)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CallParticipant`](CallParticipant.md)

Defined in: [WAProto/index.d.ts:5836](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5836)

#### Parameters

##### properties?

[`ICallParticipant`](../interfaces/ICallParticipant.md)

#### Returns

[`CallParticipant`](CallParticipant.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CallParticipant`](CallParticipant.md)

Defined in: [WAProto/index.d.ts:5838](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5838)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CallParticipant`](CallParticipant.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5837](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5837)

#### Parameters

##### m

[`ICallParticipant`](../interfaces/ICallParticipant.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CallParticipant`](CallParticipant.md)

Defined in: [WAProto/index.d.ts:5839](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5839)

#### Parameters

##### d

#### Returns

[`CallParticipant`](CallParticipant.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5842](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5842)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5840](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5840)

#### Parameters

##### m

[`CallParticipant`](CallParticipant.md)

##### o?

`IConversionOptions`

#### Returns

`object`
