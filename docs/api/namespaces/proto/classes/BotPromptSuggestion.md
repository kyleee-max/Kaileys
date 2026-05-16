# Class: BotPromptSuggestion

Defined in: [WAProto/index.d.ts:1931](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1931)

## Implements

- [`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md)

## Constructors

### new BotPromptSuggestion()

> **new BotPromptSuggestion**(`p`?): [`BotPromptSuggestion`](BotPromptSuggestion.md)

Defined in: [WAProto/index.d.ts:1932](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1932)

#### Parameters

##### p?

[`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md)

#### Returns

[`BotPromptSuggestion`](BotPromptSuggestion.md)

## Properties

### prompt?

> `optional` **prompt**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1933)

#### Implementation of

[`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md).[`prompt`](../interfaces/IBotPromptSuggestion.md#prompt)

***

### promptId?

> `optional` **promptId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1934)

#### Implementation of

[`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md).[`promptId`](../interfaces/IBotPromptSuggestion.md#promptid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1940](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1940)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPromptSuggestion`](BotPromptSuggestion.md)

Defined in: [WAProto/index.d.ts:1935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1935)

#### Parameters

##### properties?

[`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md)

#### Returns

[`BotPromptSuggestion`](BotPromptSuggestion.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPromptSuggestion`](BotPromptSuggestion.md)

Defined in: [WAProto/index.d.ts:1937](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1937)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPromptSuggestion`](BotPromptSuggestion.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1936](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1936)

#### Parameters

##### m

[`IBotPromptSuggestion`](../interfaces/IBotPromptSuggestion.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPromptSuggestion`](BotPromptSuggestion.md)

Defined in: [WAProto/index.d.ts:1938](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1938)

#### Parameters

##### d

#### Returns

[`BotPromptSuggestion`](BotPromptSuggestion.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1941](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1941)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1939](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1939)

#### Parameters

##### m

[`BotPromptSuggestion`](BotPromptSuggestion.md)

##### o?

`IConversionOptions`

#### Returns

`object`
