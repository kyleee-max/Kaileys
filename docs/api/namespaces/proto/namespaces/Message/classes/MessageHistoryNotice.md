# Class: MessageHistoryNotice

Defined in: [WAProto/index.d.ts:7496](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7496)

## Implements

- [`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

## Constructors

### new MessageHistoryNotice()

> **new MessageHistoryNotice**(`p`?): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:7497](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7497)

#### Parameters

##### p?

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7498](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7498)

#### Implementation of

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md).[`contextInfo`](../interfaces/IMessageHistoryNotice.md#contextinfo)

***

### messageHistoryMetadata?

> `optional` **messageHistoryMetadata**: `null` \| [`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:7499](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7499)

#### Implementation of

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md).[`messageHistoryMetadata`](../interfaces/IMessageHistoryNotice.md#messagehistorymetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7505)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:7500](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7500)

#### Parameters

##### properties?

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:7502](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7502)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7501](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7501)

#### Parameters

##### m

[`IMessageHistoryNotice`](../interfaces/IMessageHistoryNotice.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageHistoryNotice`](MessageHistoryNotice.md)

Defined in: [WAProto/index.d.ts:7503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7503)

#### Parameters

##### d

#### Returns

[`MessageHistoryNotice`](MessageHistoryNotice.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7506)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7504)

#### Parameters

##### m

[`MessageHistoryNotice`](MessageHistoryNotice.md)

##### o?

`IConversionOptions`

#### Returns

`object`
