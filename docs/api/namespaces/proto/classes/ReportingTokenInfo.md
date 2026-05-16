# Class: ReportingTokenInfo

Defined in: [WAProto/index.d.ts:10709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10709)

## Implements

- [`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

## Constructors

### new ReportingTokenInfo()

> **new ReportingTokenInfo**(`p`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:10710](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10710)

#### Parameters

##### p?

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

## Properties

### reportingTag?

> `optional` **reportingTag**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10711](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10711)

#### Implementation of

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md).[`reportingTag`](../interfaces/IReportingTokenInfo.md#reportingtag)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10717](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10717)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:10712](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10712)

#### Parameters

##### properties?

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:10714](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10714)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10713](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10713)

#### Parameters

##### m

[`IReportingTokenInfo`](../interfaces/IReportingTokenInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ReportingTokenInfo`](ReportingTokenInfo.md)

Defined in: [WAProto/index.d.ts:10715](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10715)

#### Parameters

##### d

#### Returns

[`ReportingTokenInfo`](ReportingTokenInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10718](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10718)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10716](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10716)

#### Parameters

##### m

[`ReportingTokenInfo`](ReportingTokenInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
