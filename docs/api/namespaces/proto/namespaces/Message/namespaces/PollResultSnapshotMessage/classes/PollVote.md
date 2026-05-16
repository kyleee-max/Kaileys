# Class: PollVote

Defined in: [WAProto/index.d.ts:8398](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8398)

## Implements

- [`IPollVote`](../interfaces/IPollVote.md)

## Constructors

### new PollVote()

> **new PollVote**(`p`?): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:8399](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8399)

#### Parameters

##### p?

[`IPollVote`](../interfaces/IPollVote.md)

#### Returns

[`PollVote`](PollVote.md)

## Properties

### optionName?

> `optional` **optionName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8400](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8400)

#### Implementation of

[`IPollVote`](../interfaces/IPollVote.md).[`optionName`](../interfaces/IPollVote.md#optionname)

***

### optionVoteCount?

> `optional` **optionVoteCount**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8401](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8401)

#### Implementation of

[`IPollVote`](../interfaces/IPollVote.md).[`optionVoteCount`](../interfaces/IPollVote.md#optionvotecount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8407](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8407)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:8402](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8402)

#### Parameters

##### properties?

[`IPollVote`](../interfaces/IPollVote.md)

#### Returns

[`PollVote`](PollVote.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:8404](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8404)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollVote`](PollVote.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8403](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8403)

#### Parameters

##### m

[`IPollVote`](../interfaces/IPollVote.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollVote`](PollVote.md)

Defined in: [WAProto/index.d.ts:8405](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8405)

#### Parameters

##### d

#### Returns

[`PollVote`](PollVote.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8408](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8408)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8406](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8406)

#### Parameters

##### m

[`PollVote`](PollVote.md)

##### o?

`IConversionOptions`

#### Returns

`object`
