# Class: CommentMetadata

Defined in: [WAProto/index.d.ts:3062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3062)

## Implements

- [`ICommentMetadata`](../interfaces/ICommentMetadata.md)

## Constructors

### new CommentMetadata()

> **new CommentMetadata**(`p`?): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:3063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3063)

#### Parameters

##### p?

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

#### Returns

[`CommentMetadata`](CommentMetadata.md)

## Properties

### commentParentKey?

> `optional` **commentParentKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:3064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3064)

#### Implementation of

[`ICommentMetadata`](../interfaces/ICommentMetadata.md).[`commentParentKey`](../interfaces/ICommentMetadata.md#commentparentkey)

***

### replyCount?

> `optional` **replyCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3065)

#### Implementation of

[`ICommentMetadata`](../interfaces/ICommentMetadata.md).[`replyCount`](../interfaces/ICommentMetadata.md#replycount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3071](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3071)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:3066](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3066)

#### Parameters

##### properties?

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

#### Returns

[`CommentMetadata`](CommentMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:3068](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3068)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CommentMetadata`](CommentMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3067](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3067)

#### Parameters

##### m

[`ICommentMetadata`](../interfaces/ICommentMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CommentMetadata`](CommentMetadata.md)

Defined in: [WAProto/index.d.ts:3069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3069)

#### Parameters

##### d

#### Returns

[`CommentMetadata`](CommentMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3072)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3070)

#### Parameters

##### m

[`CommentMetadata`](CommentMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
