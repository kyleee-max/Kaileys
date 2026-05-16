# Class: BotSuggestedPromptMetadata

Defined in: [WAProto/index.d.ts:2225](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2225)

## Implements

- [`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md)

## Constructors

### new BotSuggestedPromptMetadata()

> **new BotSuggestedPromptMetadata**(`p`?): [`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

Defined in: [WAProto/index.d.ts:2226](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2226)

#### Parameters

##### p?

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md)

#### Returns

[`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

## Properties

### promptSuggestions?

> `optional` **promptSuggestions**: `null` \| [`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:2229](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2229)

#### Implementation of

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md).[`promptSuggestions`](../interfaces/IBotSuggestedPromptMetadata.md#promptsuggestions)

***

### selectedPromptId?

> `optional` **selectedPromptId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2230)

#### Implementation of

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md).[`selectedPromptId`](../interfaces/IBotSuggestedPromptMetadata.md#selectedpromptid)

***

### selectedPromptIndex?

> `optional` **selectedPromptIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2228)

#### Implementation of

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md).[`selectedPromptIndex`](../interfaces/IBotSuggestedPromptMetadata.md#selectedpromptindex)

***

### suggestedPrompts

> **suggestedPrompts**: `string`[]

Defined in: [WAProto/index.d.ts:2227](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2227)

#### Implementation of

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md).[`suggestedPrompts`](../interfaces/IBotSuggestedPromptMetadata.md#suggestedprompts)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2236](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2236)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

Defined in: [WAProto/index.d.ts:2231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2231)

#### Parameters

##### properties?

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md)

#### Returns

[`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

Defined in: [WAProto/index.d.ts:2233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2233)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2232)

#### Parameters

##### m

[`IBotSuggestedPromptMetadata`](../interfaces/IBotSuggestedPromptMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

Defined in: [WAProto/index.d.ts:2234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2234)

#### Parameters

##### d

#### Returns

[`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2237](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2237)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2235](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2235)

#### Parameters

##### m

[`BotSuggestedPromptMetadata`](BotSuggestedPromptMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
