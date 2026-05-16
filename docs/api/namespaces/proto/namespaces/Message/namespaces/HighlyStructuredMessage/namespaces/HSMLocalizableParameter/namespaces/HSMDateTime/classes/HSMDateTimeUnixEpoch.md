# Class: HSMDateTimeUnixEpoch

Defined in: [WAProto/index.d.ts:6543](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6543)

## Implements

- [`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

## Constructors

### new HSMDateTimeUnixEpoch()

> **new HSMDateTimeUnixEpoch**(`p`?): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:6544](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6544)

#### Parameters

##### p?

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

## Properties

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6545](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6545)

#### Implementation of

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md).[`timestamp`](../interfaces/IHSMDateTimeUnixEpoch.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6551](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6551)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:6546](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6546)

#### Parameters

##### properties?

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:6548](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6548)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6547](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6547)

#### Parameters

##### m

[`IHSMDateTimeUnixEpoch`](../interfaces/IHSMDateTimeUnixEpoch.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:6549](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6549)

#### Parameters

##### d

#### Returns

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6552](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6552)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6550](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6550)

#### Parameters

##### m

[`HSMDateTimeUnixEpoch`](HSMDateTimeUnixEpoch.md)

##### o?

`IConversionOptions`

#### Returns

`object`
