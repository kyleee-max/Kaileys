# Class: BroadcastListParticipant

Defined in: [WAProto/index.d.ts:11699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11699)

## Implements

- [`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md)

## Constructors

### new BroadcastListParticipant()

> **new BroadcastListParticipant**(`p`?): [`BroadcastListParticipant`](BroadcastListParticipant.md)

Defined in: [WAProto/index.d.ts:11700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11700)

#### Parameters

##### p?

[`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md)

#### Returns

[`BroadcastListParticipant`](BroadcastListParticipant.md)

## Properties

### lidJid

> **lidJid**: `string`

Defined in: [WAProto/index.d.ts:11701](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11701)

#### Implementation of

[`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md).[`lidJid`](../interfaces/IBroadcastListParticipant.md#lidjid)

***

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11702](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11702)

#### Implementation of

[`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md).[`pnJid`](../interfaces/IBroadcastListParticipant.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11708](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11708)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BroadcastListParticipant`](BroadcastListParticipant.md)

Defined in: [WAProto/index.d.ts:11703](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11703)

#### Parameters

##### properties?

[`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md)

#### Returns

[`BroadcastListParticipant`](BroadcastListParticipant.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BroadcastListParticipant`](BroadcastListParticipant.md)

Defined in: [WAProto/index.d.ts:11705](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11705)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BroadcastListParticipant`](BroadcastListParticipant.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11704](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11704)

#### Parameters

##### m

[`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BroadcastListParticipant`](BroadcastListParticipant.md)

Defined in: [WAProto/index.d.ts:11706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11706)

#### Parameters

##### d

#### Returns

[`BroadcastListParticipant`](BroadcastListParticipant.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11709)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11707](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11707)

#### Parameters

##### m

[`BroadcastListParticipant`](BroadcastListParticipant.md)

##### o?

`IConversionOptions`

#### Returns

`object`
