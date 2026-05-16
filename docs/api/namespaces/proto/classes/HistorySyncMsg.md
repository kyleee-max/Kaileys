# Class: HistorySyncMsg

Defined in: [WAProto/index.d.ts:4588](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4588)

## Implements

- [`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

## Constructors

### new HistorySyncMsg()

> **new HistorySyncMsg**(`p`?): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:4589](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4589)

#### Parameters

##### p?

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IWebMessageInfo`](../interfaces/IWebMessageInfo.md)

Defined in: [WAProto/index.d.ts:4590](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4590)

#### Implementation of

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md).[`message`](../interfaces/IHistorySyncMsg.md#message)

***

### msgOrderId?

> `optional` **msgOrderId**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4591](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4591)

#### Implementation of

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md).[`msgOrderId`](../interfaces/IHistorySyncMsg.md#msgorderid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4597)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:4592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4592)

#### Parameters

##### properties?

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:4594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4594)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4593)

#### Parameters

##### m

[`IHistorySyncMsg`](../interfaces/IHistorySyncMsg.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HistorySyncMsg`](HistorySyncMsg.md)

Defined in: [WAProto/index.d.ts:4595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4595)

#### Parameters

##### d

#### Returns

[`HistorySyncMsg`](HistorySyncMsg.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4598)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4596)

#### Parameters

##### m

[`HistorySyncMsg`](HistorySyncMsg.md)

##### o?

`IConversionOptions`

#### Returns

`object`
