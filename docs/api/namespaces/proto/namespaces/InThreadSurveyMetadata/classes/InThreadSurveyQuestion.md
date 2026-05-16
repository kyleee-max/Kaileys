# Class: InThreadSurveyQuestion

Defined in: [WAProto/index.d.ts:4806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4806)

## Implements

- [`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md)

## Constructors

### new InThreadSurveyQuestion()

> **new InThreadSurveyQuestion**(`p`?): [`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

Defined in: [WAProto/index.d.ts:4807](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4807)

#### Parameters

##### p?

[`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md)

#### Returns

[`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

## Properties

### questionId?

> `optional` **questionId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4809)

#### Implementation of

[`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md).[`questionId`](../interfaces/IInThreadSurveyQuestion.md#questionid)

***

### questionOptions

> **questionOptions**: [`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md)[]

Defined in: [WAProto/index.d.ts:4810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4810)

#### Implementation of

[`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md).[`questionOptions`](../interfaces/IInThreadSurveyQuestion.md#questionoptions)

***

### questionText?

> `optional` **questionText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4808)

#### Implementation of

[`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md).[`questionText`](../interfaces/IInThreadSurveyQuestion.md#questiontext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4816](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4816)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

Defined in: [WAProto/index.d.ts:4811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4811)

#### Parameters

##### properties?

[`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md)

#### Returns

[`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

Defined in: [WAProto/index.d.ts:4813](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4813)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4812](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4812)

#### Parameters

##### m

[`IInThreadSurveyQuestion`](../interfaces/IInThreadSurveyQuestion.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

Defined in: [WAProto/index.d.ts:4814](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4814)

#### Parameters

##### d

#### Returns

[`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4817](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4817)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4815](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4815)

#### Parameters

##### m

[`InThreadSurveyQuestion`](InThreadSurveyQuestion.md)

##### o?

`IConversionOptions`

#### Returns

`object`
