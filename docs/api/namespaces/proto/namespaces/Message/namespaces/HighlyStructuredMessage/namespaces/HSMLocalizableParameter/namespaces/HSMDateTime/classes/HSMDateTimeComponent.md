# Class: HSMDateTimeComponent

Defined in: [WAProto/index.d.ts:6503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6503)

## Implements

- [`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

## Constructors

### new HSMDateTimeComponent()

> **new HSMDateTimeComponent**(`p`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:6504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6504)

#### Parameters

##### p?

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

## Properties

### calendar?

> `optional` **calendar**: `null` \| [`CalendarType`](../namespaces/HSMDateTimeComponent/enumerations/CalendarType.md)

Defined in: [WAProto/index.d.ts:6511](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6511)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`calendar`](../interfaces/IHSMDateTimeComponent.md#calendar)

***

### dayOfMonth?

> `optional` **dayOfMonth**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6508](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6508)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`dayOfMonth`](../interfaces/IHSMDateTimeComponent.md#dayofmonth)

***

### dayOfWeek?

> `optional` **dayOfWeek**: `null` \| [`DayOfWeekType`](../namespaces/HSMDateTimeComponent/enumerations/DayOfWeekType.md)

Defined in: [WAProto/index.d.ts:6505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6505)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`dayOfWeek`](../interfaces/IHSMDateTimeComponent.md#dayofweek)

***

### hour?

> `optional` **hour**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6509](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6509)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`hour`](../interfaces/IHSMDateTimeComponent.md#hour)

***

### minute?

> `optional` **minute**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6510](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6510)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`minute`](../interfaces/IHSMDateTimeComponent.md#minute)

***

### month?

> `optional` **month**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6507](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6507)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`month`](../interfaces/IHSMDateTimeComponent.md#month)

***

### year?

> `optional` **year**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6506)

#### Implementation of

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md).[`year`](../interfaces/IHSMDateTimeComponent.md#year)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6517](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6517)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:6512](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6512)

#### Parameters

##### properties?

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:6514](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6514)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6513)

#### Parameters

##### m

[`IHSMDateTimeComponent`](../interfaces/IHSMDateTimeComponent.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HSMDateTimeComponent`](HSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:6515](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6515)

#### Parameters

##### d

#### Returns

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6518](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6518)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6516](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6516)

#### Parameters

##### m

[`HSMDateTimeComponent`](HSMDateTimeComponent.md)

##### o?

`IConversionOptions`

#### Returns

`object`
