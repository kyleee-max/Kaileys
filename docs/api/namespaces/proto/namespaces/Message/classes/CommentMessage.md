# Class: CommentMessage

Defined in: [WAProto/index.d.ts:5944](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5944)

## Implements

- [`ICommentMessage`](../interfaces/ICommentMessage.md)

## Constructors

### new CommentMessage()

> **new CommentMessage**(`p`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:5945](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5945)

#### Parameters

##### p?

[`ICommentMessage`](../interfaces/ICommentMessage.md)

#### Returns

[`CommentMessage`](CommentMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:5946](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5946)

#### Implementation of

[`ICommentMessage`](../interfaces/ICommentMessage.md).[`message`](../interfaces/ICommentMessage.md#message)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:5947](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5947)

#### Implementation of

[`ICommentMessage`](../interfaces/ICommentMessage.md).[`targetMessageKey`](../interfaces/ICommentMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5953)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:5948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5948)

#### Parameters

##### properties?

[`ICommentMessage`](../interfaces/ICommentMessage.md)

#### Returns

[`CommentMessage`](CommentMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:5950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5950)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CommentMessage`](CommentMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5949)

#### Parameters

##### m

[`ICommentMessage`](../interfaces/ICommentMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CommentMessage`](CommentMessage.md)

Defined in: [WAProto/index.d.ts:5951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5951)

#### Parameters

##### d

#### Returns

[`CommentMessage`](CommentMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5954)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5952)

#### Parameters

##### m

[`CommentMessage`](CommentMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
