# Class: QuestionResponseMessage

Defined in: [WAProto/index.d.ts:8655](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8655)

## Implements

- [`IQuestionResponseMessage`](../interfaces/IQuestionResponseMessage.md)

## Constructors

### new QuestionResponseMessage()

> **new QuestionResponseMessage**(`p`?): [`QuestionResponseMessage`](QuestionResponseMessage.md)

Defined in: [WAProto/index.d.ts:8656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8656)

#### Parameters

##### p?

[`IQuestionResponseMessage`](../interfaces/IQuestionResponseMessage.md)

#### Returns

[`QuestionResponseMessage`](QuestionResponseMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8657)

#### Implementation of

[`IQuestionResponseMessage`](../interfaces/IQuestionResponseMessage.md).[`key`](../interfaces/IQuestionResponseMessage.md#key)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8658)

#### Implementation of

[`IQuestionResponseMessage`](../interfaces/IQuestionResponseMessage.md).[`text`](../interfaces/IQuestionResponseMessage.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8664](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8664)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`QuestionResponseMessage`](QuestionResponseMessage.md)

Defined in: [WAProto/index.d.ts:8659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8659)

#### Parameters

##### properties?

[`IQuestionResponseMessage`](../interfaces/IQuestionResponseMessage.md)

#### Returns

[`QuestionResponseMessage`](QuestionResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`QuestionResponseMessage`](QuestionResponseMessage.md)

Defined in: [WAProto/index.d.ts:8661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8661)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`QuestionResponseMessage`](QuestionResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8660)

#### Parameters

##### m

[`IQuestionResponseMessage`](../interfaces/IQuestionResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`QuestionResponseMessage`](QuestionResponseMessage.md)

Defined in: [WAProto/index.d.ts:8662](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8662)

#### Parameters

##### d

#### Returns

[`QuestionResponseMessage`](QuestionResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8665](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8665)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8663](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8663)

#### Parameters

##### m

[`QuestionResponseMessage`](QuestionResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
