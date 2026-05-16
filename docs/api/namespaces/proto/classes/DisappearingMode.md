# Class: DisappearingMode

Defined in: [WAProto/index.d.ts:4005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4005)

## Implements

- [`IDisappearingMode`](../interfaces/IDisappearingMode.md)

## Constructors

### new DisappearingMode()

> **new DisappearingMode**(`p`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:4006](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4006)

#### Parameters

##### p?

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

#### Returns

[`DisappearingMode`](DisappearingMode.md)

## Properties

### initiatedByMe?

> `optional` **initiatedByMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4010](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4010)

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiatedByMe`](../interfaces/IDisappearingMode.md#initiatedbyme)

***

### initiator?

> `optional` **initiator**: `null` \| [`Initiator`](../namespaces/DisappearingMode/enumerations/Initiator.md)

Defined in: [WAProto/index.d.ts:4007](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4007)

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiator`](../interfaces/IDisappearingMode.md#initiator)

***

### initiatorDeviceJid?

> `optional` **initiatorDeviceJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4009](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4009)

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`initiatorDeviceJid`](../interfaces/IDisappearingMode.md#initiatordevicejid)

***

### trigger?

> `optional` **trigger**: `null` \| [`Trigger`](../namespaces/DisappearingMode/enumerations/Trigger.md)

Defined in: [WAProto/index.d.ts:4008](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4008)

#### Implementation of

[`IDisappearingMode`](../interfaces/IDisappearingMode.md).[`trigger`](../interfaces/IDisappearingMode.md#trigger)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4016)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:4011](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4011)

#### Parameters

##### properties?

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

#### Returns

[`DisappearingMode`](DisappearingMode.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:4013](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4013)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DisappearingMode`](DisappearingMode.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4012](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4012)

#### Parameters

##### m

[`IDisappearingMode`](../interfaces/IDisappearingMode.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DisappearingMode`](DisappearingMode.md)

Defined in: [WAProto/index.d.ts:4014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4014)

#### Parameters

##### d

#### Returns

[`DisappearingMode`](DisappearingMode.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4017)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4015)

#### Parameters

##### m

[`DisappearingMode`](DisappearingMode.md)

##### o?

`IConversionOptions`

#### Returns

`object`
