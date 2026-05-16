# Class: PastParticipant

Defined in: [WAProto/index.d.ts:10034](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10034)

## Implements

- [`IPastParticipant`](../interfaces/IPastParticipant.md)

## Constructors

### new PastParticipant()

> **new PastParticipant**(`p`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:10035](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10035)

#### Parameters

##### p?

[`IPastParticipant`](../interfaces/IPastParticipant.md)

#### Returns

[`PastParticipant`](PastParticipant.md)

## Properties

### leaveReason?

> `optional` **leaveReason**: `null` \| [`LeaveReason`](../namespaces/PastParticipant/enumerations/LeaveReason.md)

Defined in: [WAProto/index.d.ts:10037](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10037)

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`leaveReason`](../interfaces/IPastParticipant.md#leavereason)

***

### leaveTs?

> `optional` **leaveTs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10038)

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`leaveTs`](../interfaces/IPastParticipant.md#leavets)

***

### userJid?

> `optional` **userJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10036](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10036)

#### Implementation of

[`IPastParticipant`](../interfaces/IPastParticipant.md).[`userJid`](../interfaces/IPastParticipant.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10044](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10044)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:10039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10039)

#### Parameters

##### properties?

[`IPastParticipant`](../interfaces/IPastParticipant.md)

#### Returns

[`PastParticipant`](PastParticipant.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:10041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10041)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PastParticipant`](PastParticipant.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10040)

#### Parameters

##### m

[`IPastParticipant`](../interfaces/IPastParticipant.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PastParticipant`](PastParticipant.md)

Defined in: [WAProto/index.d.ts:10042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10042)

#### Parameters

##### d

#### Returns

[`PastParticipant`](PastParticipant.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10045](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10045)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10043](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10043)

#### Parameters

##### m

[`PastParticipant`](PastParticipant.md)

##### o?

`IConversionOptions`

#### Returns

`object`
