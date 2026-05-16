# Class: SideBySideSurveyCTAClickEventData

Defined in: [WAProto/index.d.ts:1214](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1214)

## Implements

- [`ISideBySideSurveyCTAClickEventData`](../interfaces/ISideBySideSurveyCTAClickEventData.md)

## Constructors

### new SideBySideSurveyCTAClickEventData()

> **new SideBySideSurveyCTAClickEventData**(`p`?): [`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

Defined in: [WAProto/index.d.ts:1215](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1215)

#### Parameters

##### p?

[`ISideBySideSurveyCTAClickEventData`](../interfaces/ISideBySideSurveyCTAClickEventData.md)

#### Returns

[`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

## Properties

### clickDwellTimeMsString?

> `optional` **clickDwellTimeMsString**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1217](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1217)

#### Implementation of

[`ISideBySideSurveyCTAClickEventData`](../interfaces/ISideBySideSurveyCTAClickEventData.md).[`clickDwellTimeMsString`](../interfaces/ISideBySideSurveyCTAClickEventData.md#clickdwelltimemsstring)

***

### isSurveyExpired?

> `optional` **isSurveyExpired**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:1216](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1216)

#### Implementation of

[`ISideBySideSurveyCTAClickEventData`](../interfaces/ISideBySideSurveyCTAClickEventData.md).[`isSurveyExpired`](../interfaces/ISideBySideSurveyCTAClickEventData.md#issurveyexpired)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1223](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1223)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

Defined in: [WAProto/index.d.ts:1218](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1218)

#### Parameters

##### properties?

[`ISideBySideSurveyCTAClickEventData`](../interfaces/ISideBySideSurveyCTAClickEventData.md)

#### Returns

[`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

Defined in: [WAProto/index.d.ts:1220](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1220)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1219](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1219)

#### Parameters

##### m

[`ISideBySideSurveyCTAClickEventData`](../interfaces/ISideBySideSurveyCTAClickEventData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

Defined in: [WAProto/index.d.ts:1221](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1221)

#### Parameters

##### d

#### Returns

[`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1224](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1224)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1222)

#### Parameters

##### m

[`SideBySideSurveyCTAClickEventData`](SideBySideSurveyCTAClickEventData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
