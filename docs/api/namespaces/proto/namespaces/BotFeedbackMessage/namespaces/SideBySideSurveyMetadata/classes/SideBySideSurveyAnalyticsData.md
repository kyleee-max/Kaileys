# Class: SideBySideSurveyAnalyticsData

Defined in: [WAProto/index.d.ts:1145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1145)

## Implements

- [`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md)

## Constructors

### new SideBySideSurveyAnalyticsData()

> **new SideBySideSurveyAnalyticsData**(`p`?): [`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

Defined in: [WAProto/index.d.ts:1146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1146)

#### Parameters

##### p?

[`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md)

#### Returns

[`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

## Properties

### simonSessionFbid?

> `optional` **simonSessionFbid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1149](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1149)

#### Implementation of

[`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md).[`simonSessionFbid`](../interfaces/ISideBySideSurveyAnalyticsData.md#simonsessionfbid)

***

### tessaEvent?

> `optional` **tessaEvent**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1147)

#### Implementation of

[`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md).[`tessaEvent`](../interfaces/ISideBySideSurveyAnalyticsData.md#tessaevent)

***

### tessaSessionFbid?

> `optional` **tessaSessionFbid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1148)

#### Implementation of

[`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md).[`tessaSessionFbid`](../interfaces/ISideBySideSurveyAnalyticsData.md#tessasessionfbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1155](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1155)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

Defined in: [WAProto/index.d.ts:1150](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1150)

#### Parameters

##### properties?

[`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md)

#### Returns

[`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

Defined in: [WAProto/index.d.ts:1152](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1152)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1151](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1151)

#### Parameters

##### m

[`ISideBySideSurveyAnalyticsData`](../interfaces/ISideBySideSurveyAnalyticsData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

Defined in: [WAProto/index.d.ts:1153](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1153)

#### Parameters

##### d

#### Returns

[`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1156](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1156)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1154](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1154)

#### Parameters

##### m

[`SideBySideSurveyAnalyticsData`](SideBySideSurveyAnalyticsData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
