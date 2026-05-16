# Class: StatusQuestionAnswerMessage

Defined in: [WAProto/index.d.ts:8919](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8919)

## Implements

- [`IStatusQuestionAnswerMessage`](../interfaces/IStatusQuestionAnswerMessage.md)

## Constructors

### new StatusQuestionAnswerMessage()

> **new StatusQuestionAnswerMessage**(`p`?): [`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

Defined in: [WAProto/index.d.ts:8920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8920)

#### Parameters

##### p?

[`IStatusQuestionAnswerMessage`](../interfaces/IStatusQuestionAnswerMessage.md)

#### Returns

[`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8921)

#### Implementation of

[`IStatusQuestionAnswerMessage`](../interfaces/IStatusQuestionAnswerMessage.md).[`key`](../interfaces/IStatusQuestionAnswerMessage.md#key)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8922](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8922)

#### Implementation of

[`IStatusQuestionAnswerMessage`](../interfaces/IStatusQuestionAnswerMessage.md).[`text`](../interfaces/IStatusQuestionAnswerMessage.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8928)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

Defined in: [WAProto/index.d.ts:8923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8923)

#### Parameters

##### properties?

[`IStatusQuestionAnswerMessage`](../interfaces/IStatusQuestionAnswerMessage.md)

#### Returns

[`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

Defined in: [WAProto/index.d.ts:8925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8925)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8924](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8924)

#### Parameters

##### m

[`IStatusQuestionAnswerMessage`](../interfaces/IStatusQuestionAnswerMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

Defined in: [WAProto/index.d.ts:8926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8926)

#### Parameters

##### d

#### Returns

[`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8929)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8927)

#### Parameters

##### m

[`StatusQuestionAnswerMessage`](StatusQuestionAnswerMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
