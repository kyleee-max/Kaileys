# Class: SideBySideSurveyAbandonEventData

Defined in: [WAProto/index.d.ts:1197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1197)

## Implements

- [`ISideBySideSurveyAbandonEventData`](../interfaces/ISideBySideSurveyAbandonEventData.md)

## Constructors

### new SideBySideSurveyAbandonEventData()

> **new SideBySideSurveyAbandonEventData**(`p`?): [`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

Defined in: [WAProto/index.d.ts:1198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1198)

#### Parameters

##### p?

[`ISideBySideSurveyAbandonEventData`](../interfaces/ISideBySideSurveyAbandonEventData.md)

#### Returns

[`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

## Properties

### abandonDwellTimeMsString?

> `optional` **abandonDwellTimeMsString**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1199)

#### Implementation of

[`ISideBySideSurveyAbandonEventData`](../interfaces/ISideBySideSurveyAbandonEventData.md).[`abandonDwellTimeMsString`](../interfaces/ISideBySideSurveyAbandonEventData.md#abandondwelltimemsstring)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1205)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

Defined in: [WAProto/index.d.ts:1200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1200)

#### Parameters

##### properties?

[`ISideBySideSurveyAbandonEventData`](../interfaces/ISideBySideSurveyAbandonEventData.md)

#### Returns

[`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

Defined in: [WAProto/index.d.ts:1202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1202)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1201)

#### Parameters

##### m

[`ISideBySideSurveyAbandonEventData`](../interfaces/ISideBySideSurveyAbandonEventData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

Defined in: [WAProto/index.d.ts:1203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1203)

#### Parameters

##### d

#### Returns

[`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1206)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1204)

#### Parameters

##### m

[`SideBySideSurveyAbandonEventData`](SideBySideSurveyAbandonEventData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
