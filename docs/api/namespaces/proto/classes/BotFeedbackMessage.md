# Class: BotFeedbackMessage

Defined in: [WAProto/index.d.ts:1046](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1046)

## Implements

- [`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

## Constructors

### new BotFeedbackMessage()

> **new BotFeedbackMessage**(`p`?): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:1047](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1047)

#### Parameters

##### p?

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

## Properties

### kind?

> `optional` **kind**: `null` \| [`BotFeedbackKind`](../namespaces/BotFeedbackMessage/enumerations/BotFeedbackKind.md)

Defined in: [WAProto/index.d.ts:1049](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1049)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kind`](../interfaces/IBotFeedbackMessage.md#kind)

***

### kindNegative?

> `optional` **kindNegative**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:1051](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1051)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kindNegative`](../interfaces/IBotFeedbackMessage.md#kindnegative)

***

### kindPositive?

> `optional` **kindPositive**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:1052](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1052)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kindPositive`](../interfaces/IBotFeedbackMessage.md#kindpositive)

***

### kindReport?

> `optional` **kindReport**: `null` \| [`ReportKind`](../namespaces/BotFeedbackMessage/enumerations/ReportKind.md)

Defined in: [WAProto/index.d.ts:1053](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1053)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`kindReport`](../interfaces/IBotFeedbackMessage.md#kindreport)

***

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:1048](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1048)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`messageKey`](../interfaces/IBotFeedbackMessage.md#messagekey)

***

### sideBySideSurveyMetadata?

> `optional` **sideBySideSurveyMetadata**: `null` \| [`ISideBySideSurveyMetadata`](../namespaces/BotFeedbackMessage/interfaces/ISideBySideSurveyMetadata.md)

Defined in: [WAProto/index.d.ts:1054](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1054)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`sideBySideSurveyMetadata`](../interfaces/IBotFeedbackMessage.md#sidebysidesurveymetadata)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1050](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1050)

#### Implementation of

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md).[`text`](../interfaces/IBotFeedbackMessage.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1060](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1060)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:1055](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1055)

#### Parameters

##### properties?

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:1057](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1057)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1056](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1056)

#### Parameters

##### m

[`IBotFeedbackMessage`](../interfaces/IBotFeedbackMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotFeedbackMessage`](BotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:1058](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1058)

#### Parameters

##### d

#### Returns

[`BotFeedbackMessage`](BotFeedbackMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1061](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1061)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1059](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1059)

#### Parameters

##### m

[`BotFeedbackMessage`](BotFeedbackMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
