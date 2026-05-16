# Class: MarketingMessageBroadcastAction

Defined in: [WAProto/index.d.ts:12282](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12282)

## Implements

- [`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

## Constructors

### new MarketingMessageBroadcastAction()

> **new MarketingMessageBroadcastAction**(`p`?): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:12283](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12283)

#### Parameters

##### p?

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

## Properties

### repliedCount?

> `optional` **repliedCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12284](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12284)

#### Implementation of

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md).[`repliedCount`](../interfaces/IMarketingMessageBroadcastAction.md#repliedcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12290](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12290)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:12285](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12285)

#### Parameters

##### properties?

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:12287](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12287)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12286](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12286)

#### Parameters

##### m

[`IMarketingMessageBroadcastAction`](../interfaces/IMarketingMessageBroadcastAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

Defined in: [WAProto/index.d.ts:12288](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12288)

#### Parameters

##### d

#### Returns

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12291)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12289](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12289)

#### Parameters

##### m

[`MarketingMessageBroadcastAction`](MarketingMessageBroadcastAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
