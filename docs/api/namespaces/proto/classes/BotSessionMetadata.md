# Class: BotSessionMetadata

Defined in: [WAProto/index.d.ts:2091](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2091)

## Implements

- [`IBotSessionMetadata`](../interfaces/IBotSessionMetadata.md)

## Constructors

### new BotSessionMetadata()

> **new BotSessionMetadata**(`p`?): [`BotSessionMetadata`](BotSessionMetadata.md)

Defined in: [WAProto/index.d.ts:2092](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2092)

#### Parameters

##### p?

[`IBotSessionMetadata`](../interfaces/IBotSessionMetadata.md)

#### Returns

[`BotSessionMetadata`](BotSessionMetadata.md)

## Properties

### sessionId?

> `optional` **sessionId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2093](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2093)

#### Implementation of

[`IBotSessionMetadata`](../interfaces/IBotSessionMetadata.md).[`sessionId`](../interfaces/IBotSessionMetadata.md#sessionid)

***

### sessionSource?

> `optional` **sessionSource**: `null` \| [`BotSessionSource`](../enumerations/BotSessionSource.md)

Defined in: [WAProto/index.d.ts:2094](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2094)

#### Implementation of

[`IBotSessionMetadata`](../interfaces/IBotSessionMetadata.md).[`sessionSource`](../interfaces/IBotSessionMetadata.md#sessionsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2100](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2100)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotSessionMetadata`](BotSessionMetadata.md)

Defined in: [WAProto/index.d.ts:2095](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2095)

#### Parameters

##### properties?

[`IBotSessionMetadata`](../interfaces/IBotSessionMetadata.md)

#### Returns

[`BotSessionMetadata`](BotSessionMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotSessionMetadata`](BotSessionMetadata.md)

Defined in: [WAProto/index.d.ts:2097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2097)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotSessionMetadata`](BotSessionMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2096](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2096)

#### Parameters

##### m

[`IBotSessionMetadata`](../interfaces/IBotSessionMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotSessionMetadata`](BotSessionMetadata.md)

Defined in: [WAProto/index.d.ts:2098](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2098)

#### Parameters

##### d

#### Returns

[`BotSessionMetadata`](BotSessionMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2101](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2101)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2099](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2099)

#### Parameters

##### m

[`BotSessionMetadata`](BotSessionMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
