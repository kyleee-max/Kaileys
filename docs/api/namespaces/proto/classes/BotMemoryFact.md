# Class: BotMemoryFact

Defined in: [WAProto/index.d.ts:1390](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1390)

## Implements

- [`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

## Constructors

### new BotMemoryFact()

> **new BotMemoryFact**(`p`?): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:1391](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1391)

#### Parameters

##### p?

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

## Properties

### fact?

> `optional` **fact**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1392](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1392)

#### Implementation of

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md).[`fact`](../interfaces/IBotMemoryFact.md#fact)

***

### factId?

> `optional` **factId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1393](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1393)

#### Implementation of

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md).[`factId`](../interfaces/IBotMemoryFact.md#factid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1399](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1399)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:1394](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1394)

#### Parameters

##### properties?

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:1396](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1396)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1395](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1395)

#### Parameters

##### m

[`IBotMemoryFact`](../interfaces/IBotMemoryFact.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMemoryFact`](BotMemoryFact.md)

Defined in: [WAProto/index.d.ts:1397](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1397)

#### Parameters

##### d

#### Returns

[`BotMemoryFact`](BotMemoryFact.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1400](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1400)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1398](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1398)

#### Parameters

##### m

[`BotMemoryFact`](BotMemoryFact.md)

##### o?

`IConversionOptions`

#### Returns

`object`
