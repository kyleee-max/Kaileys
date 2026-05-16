# Class: SideBySideSurveyResponseEventData

Defined in: [WAProto/index.d.ts:1262](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1262)

## Implements

- [`ISideBySideSurveyResponseEventData`](../interfaces/ISideBySideSurveyResponseEventData.md)

## Constructors

### new SideBySideSurveyResponseEventData()

> **new SideBySideSurveyResponseEventData**(`p`?): [`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

Defined in: [WAProto/index.d.ts:1263](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1263)

#### Parameters

##### p?

[`ISideBySideSurveyResponseEventData`](../interfaces/ISideBySideSurveyResponseEventData.md)

#### Returns

[`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

## Properties

### responseDwellTimeMsString?

> `optional` **responseDwellTimeMsString**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1264](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1264)

#### Implementation of

[`ISideBySideSurveyResponseEventData`](../interfaces/ISideBySideSurveyResponseEventData.md).[`responseDwellTimeMsString`](../interfaces/ISideBySideSurveyResponseEventData.md#responsedwelltimemsstring)

***

### selectedResponseId?

> `optional` **selectedResponseId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1265](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1265)

#### Implementation of

[`ISideBySideSurveyResponseEventData`](../interfaces/ISideBySideSurveyResponseEventData.md).[`selectedResponseId`](../interfaces/ISideBySideSurveyResponseEventData.md#selectedresponseid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1271](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1271)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

Defined in: [WAProto/index.d.ts:1266](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1266)

#### Parameters

##### properties?

[`ISideBySideSurveyResponseEventData`](../interfaces/ISideBySideSurveyResponseEventData.md)

#### Returns

[`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

Defined in: [WAProto/index.d.ts:1268](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1268)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1267](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1267)

#### Parameters

##### m

[`ISideBySideSurveyResponseEventData`](../interfaces/ISideBySideSurveyResponseEventData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

Defined in: [WAProto/index.d.ts:1269](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1269)

#### Parameters

##### d

#### Returns

[`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1272)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1270](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1270)

#### Parameters

##### m

[`SideBySideSurveyResponseEventData`](SideBySideSurveyResponseEventData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
