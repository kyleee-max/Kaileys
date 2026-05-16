# Class: PollVotesSnapshot

Defined in: [WAProto/index.d.ts:9808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9808)

## Implements

- [`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

## Constructors

### new PollVotesSnapshot()

> **new PollVotesSnapshot**(`p`?): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:9809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9809)

#### Parameters

##### p?

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

## Properties

### pollVotes

> **pollVotes**: [`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md)[]

Defined in: [WAProto/index.d.ts:9810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9810)

#### Implementation of

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md).[`pollVotes`](../interfaces/IPollVotesSnapshot.md#pollvotes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9816](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9816)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:9811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9811)

#### Parameters

##### properties?

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:9813](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9813)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9812](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9812)

#### Parameters

##### m

[`IPollVotesSnapshot`](../interfaces/IPollVotesSnapshot.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollVotesSnapshot`](PollVotesSnapshot.md)

Defined in: [WAProto/index.d.ts:9814](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9814)

#### Parameters

##### d

#### Returns

[`PollVotesSnapshot`](PollVotesSnapshot.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9817](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9817)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9815](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9815)

#### Parameters

##### m

[`PollVotesSnapshot`](PollVotesSnapshot.md)

##### o?

`IConversionOptions`

#### Returns

`object`
