# Class: BotMemoryMetadata

Defined in: [WAProto/index.d.ts:1409](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1409)

## Implements

- [`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md)

## Constructors

### new BotMemoryMetadata()

> **new BotMemoryMetadata**(`p`?): [`BotMemoryMetadata`](BotMemoryMetadata.md)

Defined in: [WAProto/index.d.ts:1410](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1410)

#### Parameters

##### p?

[`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md)

#### Returns

[`BotMemoryMetadata`](BotMemoryMetadata.md)

## Properties

### addedFacts

> **addedFacts**: [`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)[]

Defined in: [WAProto/index.d.ts:1411](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1411)

#### Implementation of

[`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md).[`addedFacts`](../interfaces/IBotMemoryMetadata.md#addedfacts)

***

### disclaimer?

> `optional` **disclaimer**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1413)

#### Implementation of

[`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md).[`disclaimer`](../interfaces/IBotMemoryMetadata.md#disclaimer)

***

### removedFacts

> **removedFacts**: [`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)[]

Defined in: [WAProto/index.d.ts:1412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1412)

#### Implementation of

[`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md).[`removedFacts`](../interfaces/IBotMemoryMetadata.md#removedfacts)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1419)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMemoryMetadata`](BotMemoryMetadata.md)

Defined in: [WAProto/index.d.ts:1414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1414)

#### Parameters

##### properties?

[`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md)

#### Returns

[`BotMemoryMetadata`](BotMemoryMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMemoryMetadata`](BotMemoryMetadata.md)

Defined in: [WAProto/index.d.ts:1416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1416)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMemoryMetadata`](BotMemoryMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1415)

#### Parameters

##### m

[`IBotMemoryMetadata`](../interfaces/IBotMemoryMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMemoryMetadata`](BotMemoryMetadata.md)

Defined in: [WAProto/index.d.ts:1417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1417)

#### Parameters

##### d

#### Returns

[`BotMemoryMetadata`](BotMemoryMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1420)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1418)

#### Parameters

##### m

[`BotMemoryMetadata`](BotMemoryMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
