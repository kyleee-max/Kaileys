# Class: CallLogRecord

Defined in: [WAProto/index.d.ts:2317](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2317)

## Implements

- [`ICallLogRecord`](../interfaces/ICallLogRecord.md)

## Constructors

### new CallLogRecord()

> **new CallLogRecord**(`p`?): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:2318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2318)

#### Parameters

##### p?

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

#### Returns

[`CallLogRecord`](CallLogRecord.md)

## Properties

### callCreatorJid?

> `optional` **callCreatorJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2330](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2330)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callCreatorJid`](../interfaces/ICallLogRecord.md#callcreatorjid)

***

### callId?

> `optional` **callId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2329](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2329)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callId`](../interfaces/ICallLogRecord.md#callid)

***

### callLinkToken?

> `optional` **callLinkToken**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2327](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2327)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callLinkToken`](../interfaces/ICallLogRecord.md#calllinktoken)

***

### callResult?

> `optional` **callResult**: `null` \| [`CallResult`](../namespaces/CallLogRecord/enumerations/CallResult.md)

Defined in: [WAProto/index.d.ts:2319](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2319)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callResult`](../interfaces/ICallLogRecord.md#callresult)

***

### callType?

> `optional` **callType**: `null` \| [`CallType`](../namespaces/CallLogRecord/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:2333](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2333)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`callType`](../interfaces/ICallLogRecord.md#calltype)

***

### duration?

> `optional` **duration**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2322](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2322)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`duration`](../interfaces/ICallLogRecord.md#duration)

***

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2331](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2331)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`groupJid`](../interfaces/ICallLogRecord.md#groupjid)

***

### isCallLink?

> `optional` **isCallLink**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2326](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2326)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isCallLink`](../interfaces/ICallLogRecord.md#iscalllink)

***

### isDndMode?

> `optional` **isDndMode**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2320)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isDndMode`](../interfaces/ICallLogRecord.md#isdndmode)

***

### isIncoming?

> `optional` **isIncoming**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2324](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2324)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isIncoming`](../interfaces/ICallLogRecord.md#isincoming)

***

### isVideo?

> `optional` **isVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2325](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2325)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`isVideo`](../interfaces/ICallLogRecord.md#isvideo)

***

### participants

> **participants**: [`IParticipantInfo`](../namespaces/CallLogRecord/interfaces/IParticipantInfo.md)[]

Defined in: [WAProto/index.d.ts:2332](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2332)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`participants`](../interfaces/ICallLogRecord.md#participants)

***

### scheduledCallId?

> `optional` **scheduledCallId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2328](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2328)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`scheduledCallId`](../interfaces/ICallLogRecord.md#scheduledcallid)

***

### silenceReason?

> `optional` **silenceReason**: `null` \| [`SilenceReason`](../namespaces/CallLogRecord/enumerations/SilenceReason.md)

Defined in: [WAProto/index.d.ts:2321](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2321)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`silenceReason`](../interfaces/ICallLogRecord.md#silencereason)

***

### startTime?

> `optional` **startTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2323](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2323)

#### Implementation of

[`ICallLogRecord`](../interfaces/ICallLogRecord.md).[`startTime`](../interfaces/ICallLogRecord.md#starttime)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2339)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:2334](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2334)

#### Parameters

##### properties?

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

#### Returns

[`CallLogRecord`](CallLogRecord.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:2336](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2336)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CallLogRecord`](CallLogRecord.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2335](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2335)

#### Parameters

##### m

[`ICallLogRecord`](../interfaces/ICallLogRecord.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CallLogRecord`](CallLogRecord.md)

Defined in: [WAProto/index.d.ts:2337](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2337)

#### Parameters

##### d

#### Returns

[`CallLogRecord`](CallLogRecord.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2340)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2338)

#### Parameters

##### m

[`CallLogRecord`](CallLogRecord.md)

##### o?

`IConversionOptions`

#### Returns

`object`
