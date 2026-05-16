# Class: MessageHistoryMetadata

Defined in: [WAProto/index.d.ts:7477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7477)

## Implements

- [`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

## Constructors

### new MessageHistoryMetadata()

> **new MessageHistoryMetadata**(`p`?): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:7478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7478)

#### Parameters

##### p?

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

## Properties

### historyReceivers

> **historyReceivers**: `string`[]

Defined in: [WAProto/index.d.ts:7479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7479)

#### Implementation of

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md).[`historyReceivers`](../interfaces/IMessageHistoryMetadata.md#historyreceivers)

***

### messageCount?

> `optional` **messageCount**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7481)

#### Implementation of

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md).[`messageCount`](../interfaces/IMessageHistoryMetadata.md#messagecount)

***

### oldestMessageTimestamp?

> `optional` **oldestMessageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7480)

#### Implementation of

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md).[`oldestMessageTimestamp`](../interfaces/IMessageHistoryMetadata.md#oldestmessagetimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7487)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:7482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7482)

#### Parameters

##### properties?

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:7484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7484)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7483)

#### Parameters

##### m

[`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageHistoryMetadata`](MessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:7485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7485)

#### Parameters

##### d

#### Returns

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7488)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7486)

#### Parameters

##### m

[`MessageHistoryMetadata`](MessageHistoryMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
