# Class: Reaction

Defined in: [WAProto/index.d.ts:10631](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10631)

## Implements

- [`IReaction`](../interfaces/IReaction.md)

## Constructors

### new Reaction()

> **new Reaction**(`p`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:10632](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10632)

#### Parameters

##### p?

[`IReaction`](../interfaces/IReaction.md)

#### Returns

[`Reaction`](Reaction.md)

## Properties

### groupingKey?

> `optional` **groupingKey**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10635](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10635)

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`groupingKey`](../interfaces/IReaction.md#groupingkey)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:10633](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10633)

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`key`](../interfaces/IReaction.md#key)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10636](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10636)

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`senderTimestampMs`](../interfaces/IReaction.md#sendertimestampms)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10634](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10634)

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`text`](../interfaces/IReaction.md#text)

***

### unread?

> `optional` **unread**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:10637](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10637)

#### Implementation of

[`IReaction`](../interfaces/IReaction.md).[`unread`](../interfaces/IReaction.md#unread)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10643](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10643)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:10638](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10638)

#### Parameters

##### properties?

[`IReaction`](../interfaces/IReaction.md)

#### Returns

[`Reaction`](Reaction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:10640](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10640)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Reaction`](Reaction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10639](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10639)

#### Parameters

##### m

[`IReaction`](../interfaces/IReaction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Reaction`](Reaction.md)

Defined in: [WAProto/index.d.ts:10641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10641)

#### Parameters

##### d

#### Returns

[`Reaction`](Reaction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10644](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10644)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10642](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10642)

#### Parameters

##### m

[`Reaction`](Reaction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
