# Class: EphemeralSetting

Defined in: [WAProto/index.d.ts:4141](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4141)

## Implements

- [`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

## Constructors

### new EphemeralSetting()

> **new EphemeralSetting**(`p`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:4142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4142)

#### Parameters

##### p?

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

## Properties

### duration?

> `optional` **duration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4143](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4143)

#### Implementation of

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md).[`duration`](../interfaces/IEphemeralSetting.md#duration)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4144)

#### Implementation of

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md).[`timestamp`](../interfaces/IEphemeralSetting.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4150](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4150)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:4145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4145)

#### Parameters

##### properties?

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:4147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4147)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4146)

#### Parameters

##### m

[`IEphemeralSetting`](../interfaces/IEphemeralSetting.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EphemeralSetting`](EphemeralSetting.md)

Defined in: [WAProto/index.d.ts:4148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4148)

#### Parameters

##### d

#### Returns

[`EphemeralSetting`](EphemeralSetting.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4151](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4151)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4149](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4149)

#### Parameters

##### m

[`EphemeralSetting`](EphemeralSetting.md)

##### o?

`IConversionOptions`

#### Returns

`object`
