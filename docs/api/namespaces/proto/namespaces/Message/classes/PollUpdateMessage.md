# Class: PollUpdateMessage

Defined in: [WAProto/index.d.ts:8424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8424)

## Implements

- [`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

## Constructors

### new PollUpdateMessage()

> **new PollUpdateMessage**(`p`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:8425](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8425)

#### Parameters

##### p?

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

## Properties

### metadata?

> `optional` **metadata**: `null` \| [`IPollUpdateMessageMetadata`](../interfaces/IPollUpdateMessageMetadata.md)

Defined in: [WAProto/index.d.ts:8428](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8428)

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`metadata`](../interfaces/IPollUpdateMessage.md#metadata)

***

### pollCreationMessageKey?

> `optional` **pollCreationMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8426](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8426)

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`pollCreationMessageKey`](../interfaces/IPollUpdateMessage.md#pollcreationmessagekey)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8429](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8429)

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`senderTimestampMs`](../interfaces/IPollUpdateMessage.md#sendertimestampms)

***

### vote?

> `optional` **vote**: `null` \| [`IPollEncValue`](../interfaces/IPollEncValue.md)

Defined in: [WAProto/index.d.ts:8427](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8427)

#### Implementation of

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md).[`vote`](../interfaces/IPollUpdateMessage.md#vote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8435)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:8430](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8430)

#### Parameters

##### properties?

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:8432](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8432)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8431](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8431)

#### Parameters

##### m

[`IPollUpdateMessage`](../interfaces/IPollUpdateMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollUpdateMessage`](PollUpdateMessage.md)

Defined in: [WAProto/index.d.ts:8433](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8433)

#### Parameters

##### d

#### Returns

[`PollUpdateMessage`](PollUpdateMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8436](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8436)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8434)

#### Parameters

##### m

[`PollUpdateMessage`](PollUpdateMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
