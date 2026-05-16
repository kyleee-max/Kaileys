# Class: AIRichResponseMessage

Defined in: [WAProto/index.d.ts:545](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L545)

## Implements

- [`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

## Constructors

### new AIRichResponseMessage()

> **new AIRichResponseMessage**(`p`?): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:546](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L546)

#### Parameters

##### p?

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:550](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L550)

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`contextInfo`](../interfaces/IAIRichResponseMessage.md#contextinfo)

***

### messageType?

> `optional` **messageType**: `null` \| [`AIRichResponseMessageType`](../enumerations/AIRichResponseMessageType.md)

Defined in: [WAProto/index.d.ts:547](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L547)

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`messageType`](../interfaces/IAIRichResponseMessage.md#messagetype)

***

### submessages

> **submessages**: [`IAIRichResponseSubMessage`](../interfaces/IAIRichResponseSubMessage.md)[]

Defined in: [WAProto/index.d.ts:548](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L548)

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`submessages`](../interfaces/IAIRichResponseMessage.md#submessages)

***

### unifiedResponse?

> `optional` **unifiedResponse**: `null` \| [`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:549](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L549)

#### Implementation of

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md).[`unifiedResponse`](../interfaces/IAIRichResponseMessage.md#unifiedresponse)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:556](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L556)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:551](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L551)

#### Parameters

##### properties?

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:553](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L553)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:552](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L552)

#### Parameters

##### m

[`IAIRichResponseMessage`](../interfaces/IAIRichResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseMessage`](AIRichResponseMessage.md)

Defined in: [WAProto/index.d.ts:554](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L554)

#### Parameters

##### d

#### Returns

[`AIRichResponseMessage`](AIRichResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:557](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L557)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:555](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L555)

#### Parameters

##### m

[`AIRichResponseMessage`](AIRichResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
