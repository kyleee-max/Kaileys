# Class: PollVoteSnapshot

Defined in: [WAProto/index.d.ts:9791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9791)

## Implements

- [`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md)

## Constructors

### new PollVoteSnapshot()

> **new PollVoteSnapshot**(`p`?): [`PollVoteSnapshot`](PollVoteSnapshot.md)

Defined in: [WAProto/index.d.ts:9792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9792)

#### Parameters

##### p?

[`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md)

#### Returns

[`PollVoteSnapshot`](PollVoteSnapshot.md)

## Properties

### option?

> `optional` **option**: `null` \| [`IPollOption`](../interfaces/IPollOption.md)

Defined in: [WAProto/index.d.ts:9793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9793)

#### Implementation of

[`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md).[`option`](../interfaces/IPollVoteSnapshot.md#option)

***

### optionVoteCount?

> `optional` **optionVoteCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9794](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9794)

#### Implementation of

[`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md).[`optionVoteCount`](../interfaces/IPollVoteSnapshot.md#optionvotecount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9800)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollVoteSnapshot`](PollVoteSnapshot.md)

Defined in: [WAProto/index.d.ts:9795](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9795)

#### Parameters

##### properties?

[`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md)

#### Returns

[`PollVoteSnapshot`](PollVoteSnapshot.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollVoteSnapshot`](PollVoteSnapshot.md)

Defined in: [WAProto/index.d.ts:9797](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9797)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollVoteSnapshot`](PollVoteSnapshot.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9796](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9796)

#### Parameters

##### m

[`IPollVoteSnapshot`](../interfaces/IPollVoteSnapshot.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollVoteSnapshot`](PollVoteSnapshot.md)

Defined in: [WAProto/index.d.ts:9798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9798)

#### Parameters

##### d

#### Returns

[`PollVoteSnapshot`](PollVoteSnapshot.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9801)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9799](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9799)

#### Parameters

##### m

[`PollVoteSnapshot`](PollVoteSnapshot.md)

##### o?

`IConversionOptions`

#### Returns

`object`
