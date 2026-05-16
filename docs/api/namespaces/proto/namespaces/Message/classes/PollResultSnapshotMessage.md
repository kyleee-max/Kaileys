# Class: PollResultSnapshotMessage

Defined in: [WAProto/index.d.ts:8376](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8376)

## Implements

- [`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

## Constructors

### new PollResultSnapshotMessage()

> **new PollResultSnapshotMessage**(`p`?): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:8377](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8377)

#### Parameters

##### p?

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:8380](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8380)

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`contextInfo`](../interfaces/IPollResultSnapshotMessage.md#contextinfo)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8378](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8378)

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`name`](../interfaces/IPollResultSnapshotMessage.md#name)

***

### pollType?

> `optional` **pollType**: `null` \| [`PollType`](../enumerations/PollType.md)

Defined in: [WAProto/index.d.ts:8381](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8381)

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`pollType`](../interfaces/IPollResultSnapshotMessage.md#polltype)

***

### pollVotes

> **pollVotes**: [`IPollVote`](../namespaces/PollResultSnapshotMessage/interfaces/IPollVote.md)[]

Defined in: [WAProto/index.d.ts:8379](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8379)

#### Implementation of

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md).[`pollVotes`](../interfaces/IPollResultSnapshotMessage.md#pollvotes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8387](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8387)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:8382](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8382)

#### Parameters

##### properties?

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:8384](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8384)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8383](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8383)

#### Parameters

##### m

[`IPollResultSnapshotMessage`](../interfaces/IPollResultSnapshotMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

Defined in: [WAProto/index.d.ts:8385](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8385)

#### Parameters

##### d

#### Returns

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8388](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8388)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8386](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8386)

#### Parameters

##### m

[`PollResultSnapshotMessage`](PollResultSnapshotMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
