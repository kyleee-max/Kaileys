# Class: Reportable

Defined in: [WAProto/index.d.ts:10690](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10690)

## Implements

- [`IReportable`](../interfaces/IReportable.md)

## Constructors

### new Reportable()

> **new Reportable**(`p`?): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:10691](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10691)

#### Parameters

##### p?

[`IReportable`](../interfaces/IReportable.md)

#### Returns

[`Reportable`](Reportable.md)

## Properties

### maxVersion?

> `optional` **maxVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10693](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10693)

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`maxVersion`](../interfaces/IReportable.md#maxversion)

***

### minVersion?

> `optional` **minVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10692](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10692)

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`minVersion`](../interfaces/IReportable.md#minversion)

***

### never?

> `optional` **never**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:10695](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10695)

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`never`](../interfaces/IReportable.md#never)

***

### notReportableMinVersion?

> `optional` **notReportableMinVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10694](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10694)

#### Implementation of

[`IReportable`](../interfaces/IReportable.md).[`notReportableMinVersion`](../interfaces/IReportable.md#notreportableminversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10701](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10701)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:10696](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10696)

#### Parameters

##### properties?

[`IReportable`](../interfaces/IReportable.md)

#### Returns

[`Reportable`](Reportable.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:10698](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10698)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Reportable`](Reportable.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10697](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10697)

#### Parameters

##### m

[`IReportable`](../interfaces/IReportable.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Reportable`](Reportable.md)

Defined in: [WAProto/index.d.ts:10699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10699)

#### Parameters

##### d

#### Returns

[`Reportable`](Reportable.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10702](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10702)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10700)

#### Parameters

##### m

[`Reportable`](Reportable.md)

##### o?

`IConversionOptions`

#### Returns

`object`
