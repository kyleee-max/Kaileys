# Class: SideBySideSurveyCTAImpressionEventData

Defined in: [WAProto/index.d.ts:1231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1231)

## Implements

- [`ISideBySideSurveyCTAImpressionEventData`](../interfaces/ISideBySideSurveyCTAImpressionEventData.md)

## Constructors

### new SideBySideSurveyCTAImpressionEventData()

> **new SideBySideSurveyCTAImpressionEventData**(`p`?): [`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

Defined in: [WAProto/index.d.ts:1232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1232)

#### Parameters

##### p?

[`ISideBySideSurveyCTAImpressionEventData`](../interfaces/ISideBySideSurveyCTAImpressionEventData.md)

#### Returns

[`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

## Properties

### isSurveyExpired?

> `optional` **isSurveyExpired**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:1233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1233)

#### Implementation of

[`ISideBySideSurveyCTAImpressionEventData`](../interfaces/ISideBySideSurveyCTAImpressionEventData.md).[`isSurveyExpired`](../interfaces/ISideBySideSurveyCTAImpressionEventData.md#issurveyexpired)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1239](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1239)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

Defined in: [WAProto/index.d.ts:1234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1234)

#### Parameters

##### properties?

[`ISideBySideSurveyCTAImpressionEventData`](../interfaces/ISideBySideSurveyCTAImpressionEventData.md)

#### Returns

[`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

Defined in: [WAProto/index.d.ts:1236](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1236)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1235](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1235)

#### Parameters

##### m

[`ISideBySideSurveyCTAImpressionEventData`](../interfaces/ISideBySideSurveyCTAImpressionEventData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

Defined in: [WAProto/index.d.ts:1237](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1237)

#### Parameters

##### d

#### Returns

[`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1240](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1240)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1238](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1238)

#### Parameters

##### m

[`SideBySideSurveyCTAImpressionEventData`](SideBySideSurveyCTAImpressionEventData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
