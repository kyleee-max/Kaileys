# Class: QuickReplyAction

Defined in: [WAProto/index.d.ts:12654](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12654)

## Implements

- [`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

## Constructors

### new QuickReplyAction()

> **new QuickReplyAction**(`p`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:12655](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12655)

#### Parameters

##### p?

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

## Properties

### count?

> `optional` **count**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12659)

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`count`](../interfaces/IQuickReplyAction.md#count)

***

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12660)

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`deleted`](../interfaces/IQuickReplyAction.md#deleted)

***

### keywords

> **keywords**: `string`[]

Defined in: [WAProto/index.d.ts:12658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12658)

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`keywords`](../interfaces/IQuickReplyAction.md#keywords)

***

### message?

> `optional` **message**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12657)

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`message`](../interfaces/IQuickReplyAction.md#message)

***

### shortcut?

> `optional` **shortcut**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12656)

#### Implementation of

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md).[`shortcut`](../interfaces/IQuickReplyAction.md#shortcut)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12666](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12666)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:12661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12661)

#### Parameters

##### properties?

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:12663](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12663)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12662](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12662)

#### Parameters

##### m

[`IQuickReplyAction`](../interfaces/IQuickReplyAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`QuickReplyAction`](QuickReplyAction.md)

Defined in: [WAProto/index.d.ts:12664](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12664)

#### Parameters

##### d

#### Returns

[`QuickReplyAction`](QuickReplyAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12667](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12667)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12665](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12665)

#### Parameters

##### m

[`QuickReplyAction`](QuickReplyAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
