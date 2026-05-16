# Class: CallLogMessage

Defined in: [WAProto/index.d.ts:5798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5798)

## Implements

- [`ICallLogMessage`](../interfaces/ICallLogMessage.md)

## Constructors

### new CallLogMessage()

> **new CallLogMessage**(`p`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:5799](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5799)

#### Parameters

##### p?

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

#### Returns

[`CallLogMessage`](CallLogMessage.md)

## Properties

### callOutcome?

> `optional` **callOutcome**: `null` \| [`CallOutcome`](../namespaces/CallLogMessage/enumerations/CallOutcome.md)

Defined in: [WAProto/index.d.ts:5801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5801)

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`callOutcome`](../interfaces/ICallLogMessage.md#calloutcome)

***

### callType?

> `optional` **callType**: `null` \| [`CallType`](../namespaces/CallLogMessage/enumerations/CallType.md)

Defined in: [WAProto/index.d.ts:5803](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5803)

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`callType`](../interfaces/ICallLogMessage.md#calltype)

***

### durationSecs?

> `optional` **durationSecs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5802](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5802)

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`durationSecs`](../interfaces/ICallLogMessage.md#durationsecs)

***

### isVideo?

> `optional` **isVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:5800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5800)

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`isVideo`](../interfaces/ICallLogMessage.md#isvideo)

***

### participants

> **participants**: [`ICallParticipant`](../namespaces/CallLogMessage/interfaces/ICallParticipant.md)[]

Defined in: [WAProto/index.d.ts:5804](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5804)

#### Implementation of

[`ICallLogMessage`](../interfaces/ICallLogMessage.md).[`participants`](../interfaces/ICallLogMessage.md#participants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5810)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:5805](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5805)

#### Parameters

##### properties?

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

#### Returns

[`CallLogMessage`](CallLogMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:5807](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5807)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CallLogMessage`](CallLogMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5806)

#### Parameters

##### m

[`ICallLogMessage`](../interfaces/ICallLogMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CallLogMessage`](CallLogMessage.md)

Defined in: [WAProto/index.d.ts:5808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5808)

#### Parameters

##### d

#### Returns

[`CallLogMessage`](CallLogMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5811)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5809)

#### Parameters

##### m

[`CallLogMessage`](CallLogMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
