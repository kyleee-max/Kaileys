# Class: BotPromptSuggestions

Defined in: [WAProto/index.d.ts:1948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1948)

## Implements

- [`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

## Constructors

### new BotPromptSuggestions()

> **new BotPromptSuggestions**(`p`?): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:1949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1949)

#### Parameters

##### p?

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

## Properties

### suggestions

> **suggestions**: [`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md)[]

Defined in: [WAProto/index.d.ts:1950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1950)

#### Implementation of

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md).[`suggestions`](../interfaces/IBotPromptSuggestions.md#suggestions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1956)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:1951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1951)

#### Parameters

##### properties?

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:1953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1953)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1952)

#### Parameters

##### m

[`IBotPromptSuggestions`](../interfaces/IBotPromptSuggestions.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPromptSuggestions`](BotPromptSuggestions.md)

Defined in: [WAProto/index.d.ts:1954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1954)

#### Parameters

##### d

#### Returns

[`BotPromptSuggestions`](BotPromptSuggestions.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1957](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1957)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1955)

#### Parameters

##### m

[`BotPromptSuggestions`](BotPromptSuggestions.md)

##### o?

`IConversionOptions`

#### Returns

`object`
