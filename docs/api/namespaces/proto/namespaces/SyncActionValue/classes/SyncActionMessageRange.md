# Class: SyncActionMessageRange

Defined in: [WAProto/index.d.ts:12846](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12846)

## Implements

- [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

## Constructors

### new SyncActionMessageRange()

> **new SyncActionMessageRange**(`p`?): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:12847](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12847)

#### Parameters

##### p?

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

## Properties

### lastMessageTimestamp?

> `optional` **lastMessageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12848](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12848)

#### Implementation of

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md).[`lastMessageTimestamp`](../interfaces/ISyncActionMessageRange.md#lastmessagetimestamp)

***

### lastSystemMessageTimestamp?

> `optional` **lastSystemMessageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12849](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12849)

#### Implementation of

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md).[`lastSystemMessageTimestamp`](../interfaces/ISyncActionMessageRange.md#lastsystemmessagetimestamp)

***

### messages

> **messages**: [`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)[]

Defined in: [WAProto/index.d.ts:12850](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12850)

#### Implementation of

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md).[`messages`](../interfaces/ISyncActionMessageRange.md#messages)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12856](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12856)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:12851](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12851)

#### Parameters

##### properties?

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:12853](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12853)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12852](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12852)

#### Parameters

##### m

[`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncActionMessageRange`](SyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:12854](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12854)

#### Parameters

##### d

#### Returns

[`SyncActionMessageRange`](SyncActionMessageRange.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12857](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12857)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12855](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12855)

#### Parameters

##### m

[`SyncActionMessageRange`](SyncActionMessageRange.md)

##### o?

`IConversionOptions`

#### Returns

`object`
