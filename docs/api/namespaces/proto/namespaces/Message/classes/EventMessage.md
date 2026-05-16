# Class: EventMessage

Defined in: [WAProto/index.d.ts:6166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6166)

## Implements

- [`IEventMessage`](../interfaces/IEventMessage.md)

## Constructors

### new EventMessage()

> **new EventMessage**(`p`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:6167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6167)

#### Parameters

##### p?

[`IEventMessage`](../interfaces/IEventMessage.md)

#### Returns

[`EventMessage`](EventMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:6168](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6168)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`contextInfo`](../interfaces/IEventMessage.md#contextinfo)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6171](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6171)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`description`](../interfaces/IEventMessage.md#description)

***

### endTime?

> `optional` **endTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6175)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`endTime`](../interfaces/IEventMessage.md#endtime)

***

### extraGuestsAllowed?

> `optional` **extraGuestsAllowed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6176)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`extraGuestsAllowed`](../interfaces/IEventMessage.md#extraguestsallowed)

***

### hasReminder?

> `optional` **hasReminder**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6178)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`hasReminder`](../interfaces/IEventMessage.md#hasreminder)

***

### isCanceled?

> `optional` **isCanceled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6169](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6169)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`isCanceled`](../interfaces/IEventMessage.md#iscanceled)

***

### isScheduleCall?

> `optional` **isScheduleCall**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6177)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`isScheduleCall`](../interfaces/IEventMessage.md#isschedulecall)

***

### joinLink?

> `optional` **joinLink**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6173)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`joinLink`](../interfaces/IEventMessage.md#joinlink)

***

### location?

> `optional` **location**: `null` \| [`ILocationMessage`](../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:6172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6172)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`location`](../interfaces/IEventMessage.md#location)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6170](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6170)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`name`](../interfaces/IEventMessage.md#name)

***

### reminderOffsetSec?

> `optional` **reminderOffsetSec**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6179)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`reminderOffsetSec`](../interfaces/IEventMessage.md#reminderoffsetsec)

***

### startTime?

> `optional` **startTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6174)

#### Implementation of

[`IEventMessage`](../interfaces/IEventMessage.md).[`startTime`](../interfaces/IEventMessage.md#starttime)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6185](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6185)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:6180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6180)

#### Parameters

##### properties?

[`IEventMessage`](../interfaces/IEventMessage.md)

#### Returns

[`EventMessage`](EventMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:6182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6182)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EventMessage`](EventMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6181)

#### Parameters

##### m

[`IEventMessage`](../interfaces/IEventMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EventMessage`](EventMessage.md)

Defined in: [WAProto/index.d.ts:6183](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6183)

#### Parameters

##### d

#### Returns

[`EventMessage`](EventMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6186](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6186)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6184](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6184)

#### Parameters

##### m

[`EventMessage`](EventMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
