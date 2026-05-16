# Class: PastParticipants

Defined in: [WAProto/index.d.ts:10061](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10061)

## Implements

- [`IPastParticipants`](../interfaces/IPastParticipants.md)

## Constructors

### new PastParticipants()

> **new PastParticipants**(`p`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:10062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10062)

#### Parameters

##### p?

[`IPastParticipants`](../interfaces/IPastParticipants.md)

#### Returns

[`PastParticipants`](PastParticipants.md)

## Properties

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10063)

#### Implementation of

[`IPastParticipants`](../interfaces/IPastParticipants.md).[`groupJid`](../interfaces/IPastParticipants.md#groupjid)

***

### pastParticipants

> **pastParticipants**: [`IPastParticipant`](../interfaces/IPastParticipant.md)[]

Defined in: [WAProto/index.d.ts:10064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10064)

#### Implementation of

[`IPastParticipants`](../interfaces/IPastParticipants.md).[`pastParticipants`](../interfaces/IPastParticipants.md#pastparticipants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10070)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:10065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10065)

#### Parameters

##### properties?

[`IPastParticipants`](../interfaces/IPastParticipants.md)

#### Returns

[`PastParticipants`](PastParticipants.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:10067](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10067)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PastParticipants`](PastParticipants.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10066](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10066)

#### Parameters

##### m

[`IPastParticipants`](../interfaces/IPastParticipants.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PastParticipants`](PastParticipants.md)

Defined in: [WAProto/index.d.ts:10068](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10068)

#### Parameters

##### d

#### Returns

[`PastParticipants`](PastParticipants.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10071](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10071)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10069)

#### Parameters

##### m

[`PastParticipants`](PastParticipants.md)

##### o?

`IConversionOptions`

#### Returns

`object`
