# Class: QuickReplyButton

Defined in: [WAProto/index.d.ts:13220](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13220)

## Implements

- [`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

## Constructors

### new QuickReplyButton()

> **new QuickReplyButton**(`p`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:13221](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13221)

#### Parameters

##### p?

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:13222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13222)

#### Implementation of

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md).[`displayText`](../interfaces/IQuickReplyButton.md#displaytext)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13223](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13223)

#### Implementation of

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md).[`id`](../interfaces/IQuickReplyButton.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13229](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13229)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:13224](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13224)

#### Parameters

##### properties?

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:13226](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13226)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13225](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13225)

#### Parameters

##### m

[`IQuickReplyButton`](../interfaces/IQuickReplyButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`QuickReplyButton`](QuickReplyButton.md)

Defined in: [WAProto/index.d.ts:13227](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13227)

#### Parameters

##### d

#### Returns

[`QuickReplyButton`](QuickReplyButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13230)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13228)

#### Parameters

##### m

[`QuickReplyButton`](QuickReplyButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
