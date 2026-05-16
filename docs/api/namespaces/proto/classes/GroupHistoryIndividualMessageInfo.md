# Class: GroupHistoryIndividualMessageInfo

Defined in: [WAProto/index.d.ts:4368](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4368)

## Implements

- [`IGroupHistoryIndividualMessageInfo`](../interfaces/IGroupHistoryIndividualMessageInfo.md)

## Constructors

### new GroupHistoryIndividualMessageInfo()

> **new GroupHistoryIndividualMessageInfo**(`p`?): [`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

Defined in: [WAProto/index.d.ts:4369](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4369)

#### Parameters

##### p?

[`IGroupHistoryIndividualMessageInfo`](../interfaces/IGroupHistoryIndividualMessageInfo.md)

#### Returns

[`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

## Properties

### bundleMessageKey?

> `optional` **bundleMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:4370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4370)

#### Implementation of

[`IGroupHistoryIndividualMessageInfo`](../interfaces/IGroupHistoryIndividualMessageInfo.md).[`bundleMessageKey`](../interfaces/IGroupHistoryIndividualMessageInfo.md#bundlemessagekey)

***

### editedAfterReceivedAsHistory?

> `optional` **editedAfterReceivedAsHistory**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4371)

#### Implementation of

[`IGroupHistoryIndividualMessageInfo`](../interfaces/IGroupHistoryIndividualMessageInfo.md).[`editedAfterReceivedAsHistory`](../interfaces/IGroupHistoryIndividualMessageInfo.md#editedafterreceivedashistory)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4377](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4377)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

Defined in: [WAProto/index.d.ts:4372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4372)

#### Parameters

##### properties?

[`IGroupHistoryIndividualMessageInfo`](../interfaces/IGroupHistoryIndividualMessageInfo.md)

#### Returns

[`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

Defined in: [WAProto/index.d.ts:4374](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4374)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4373)

#### Parameters

##### m

[`IGroupHistoryIndividualMessageInfo`](../interfaces/IGroupHistoryIndividualMessageInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

Defined in: [WAProto/index.d.ts:4375](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4375)

#### Parameters

##### d

#### Returns

[`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4378](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4378)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4376](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4376)

#### Parameters

##### m

[`GroupHistoryIndividualMessageInfo`](GroupHistoryIndividualMessageInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
