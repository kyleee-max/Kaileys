# Class: PollUpdate

Defined in: [WAProto/index.d.ts:10427](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10427)

## Implements

- [`IPollUpdate`](../interfaces/IPollUpdate.md)

## Constructors

### new PollUpdate()

> **new PollUpdate**(`p`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:10428](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10428)

#### Parameters

##### p?

[`IPollUpdate`](../interfaces/IPollUpdate.md)

#### Returns

[`PollUpdate`](PollUpdate.md)

## Properties

### pollUpdateMessageKey?

> `optional` **pollUpdateMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:10429](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10429)

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`pollUpdateMessageKey`](../interfaces/IPollUpdate.md#pollupdatemessagekey)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10431](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10431)

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`senderTimestampMs`](../interfaces/IPollUpdate.md#sendertimestampms)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10432](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10432)

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`serverTimestampMs`](../interfaces/IPollUpdate.md#servertimestampms)

***

### unread?

> `optional` **unread**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:10433](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10433)

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`unread`](../interfaces/IPollUpdate.md#unread)

***

### vote?

> `optional` **vote**: `null` \| [`IPollVoteMessage`](../namespaces/Message/interfaces/IPollVoteMessage.md)

Defined in: [WAProto/index.d.ts:10430](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10430)

#### Implementation of

[`IPollUpdate`](../interfaces/IPollUpdate.md).[`vote`](../interfaces/IPollUpdate.md#vote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10439)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:10434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10434)

#### Parameters

##### properties?

[`IPollUpdate`](../interfaces/IPollUpdate.md)

#### Returns

[`PollUpdate`](PollUpdate.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:10436](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10436)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollUpdate`](PollUpdate.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10435)

#### Parameters

##### m

[`IPollUpdate`](../interfaces/IPollUpdate.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollUpdate`](PollUpdate.md)

Defined in: [WAProto/index.d.ts:10437](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10437)

#### Parameters

##### d

#### Returns

[`PollUpdate`](PollUpdate.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10440)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10438](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10438)

#### Parameters

##### m

[`PollUpdate`](PollUpdate.md)

##### o?

`IConversionOptions`

#### Returns

`object`
