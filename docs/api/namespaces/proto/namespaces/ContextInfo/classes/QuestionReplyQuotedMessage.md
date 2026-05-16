# Class: QuestionReplyQuotedMessage

Defined in: [WAProto/index.d.ts:3522](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3522)

## Implements

- [`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md)

## Constructors

### new QuestionReplyQuotedMessage()

> **new QuestionReplyQuotedMessage**(`p`?): [`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

Defined in: [WAProto/index.d.ts:3523](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3523)

#### Parameters

##### p?

[`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md)

#### Returns

[`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

## Properties

### quotedQuestion?

> `optional` **quotedQuestion**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:3525](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3525)

#### Implementation of

[`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md).[`quotedQuestion`](../interfaces/IQuestionReplyQuotedMessage.md#quotedquestion)

***

### quotedResponse?

> `optional` **quotedResponse**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:3526](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3526)

#### Implementation of

[`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md).[`quotedResponse`](../interfaces/IQuestionReplyQuotedMessage.md#quotedresponse)

***

### serverQuestionId?

> `optional` **serverQuestionId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3524](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3524)

#### Implementation of

[`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md).[`serverQuestionId`](../interfaces/IQuestionReplyQuotedMessage.md#serverquestionid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3532](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3532)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

Defined in: [WAProto/index.d.ts:3527](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3527)

#### Parameters

##### properties?

[`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md)

#### Returns

[`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

Defined in: [WAProto/index.d.ts:3529](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3529)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3528](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3528)

#### Parameters

##### m

[`IQuestionReplyQuotedMessage`](../interfaces/IQuestionReplyQuotedMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

Defined in: [WAProto/index.d.ts:3530](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3530)

#### Parameters

##### d

#### Returns

[`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3533](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3533)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3531](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3531)

#### Parameters

##### m

[`QuestionReplyQuotedMessage`](QuestionReplyQuotedMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
