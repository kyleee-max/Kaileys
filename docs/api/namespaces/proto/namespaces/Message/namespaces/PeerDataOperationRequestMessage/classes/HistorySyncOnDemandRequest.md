# Class: HistorySyncOnDemandRequest

Defined in: [WAProto/index.d.ts:7853](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7853)

## Implements

- [`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

## Constructors

### new HistorySyncOnDemandRequest()

> **new HistorySyncOnDemandRequest**(`p`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7854](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7854)

#### Parameters

##### p?

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

## Properties

### accountLid?

> `optional` **accountLid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7860](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7860)

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`accountLid`](../interfaces/IHistorySyncOnDemandRequest.md#accountlid)

***

### chatJid?

> `optional` **chatJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7855](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7855)

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`chatJid`](../interfaces/IHistorySyncOnDemandRequest.md#chatjid)

***

### oldestMsgFromMe?

> `optional` **oldestMsgFromMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:7857](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7857)

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgFromMe`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgfromme)

***

### oldestMsgId?

> `optional` **oldestMsgId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7856](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7856)

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgId`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgid)

***

### oldestMsgTimestampMs?

> `optional` **oldestMsgTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7859](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7859)

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`oldestMsgTimestampMs`](../interfaces/IHistorySyncOnDemandRequest.md#oldestmsgtimestampms)

***

### onDemandMsgCount?

> `optional` **onDemandMsgCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7858](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7858)

#### Implementation of

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md).[`onDemandMsgCount`](../interfaces/IHistorySyncOnDemandRequest.md#ondemandmsgcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7866](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7866)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7861](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7861)

#### Parameters

##### properties?

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7863](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7863)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7862](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7862)

#### Parameters

##### m

[`IHistorySyncOnDemandRequest`](../interfaces/IHistorySyncOnDemandRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7864](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7864)

#### Parameters

##### d

#### Returns

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7867](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7867)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7865](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7865)

#### Parameters

##### m

[`HistorySyncOnDemandRequest`](HistorySyncOnDemandRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
