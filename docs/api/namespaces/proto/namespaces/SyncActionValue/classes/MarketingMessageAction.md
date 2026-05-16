# Class: MarketingMessageAction

Defined in: [WAProto/index.d.ts:12253](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12253)

## Implements

- [`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

## Constructors

### new MarketingMessageAction()

> **new MarketingMessageAction**(`p`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:12254](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12254)

#### Parameters

##### p?

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

## Properties

### createdAt?

> `optional` **createdAt**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12258](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12258)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`createdAt`](../interfaces/IMarketingMessageAction.md#createdat)

***

### isDeleted?

> `optional` **isDeleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12260](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12260)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`isDeleted`](../interfaces/IMarketingMessageAction.md#isdeleted)

***

### lastSentAt?

> `optional` **lastSentAt**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12259](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12259)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`lastSentAt`](../interfaces/IMarketingMessageAction.md#lastsentat)

***

### mediaId?

> `optional` **mediaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12261](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12261)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`mediaId`](../interfaces/IMarketingMessageAction.md#mediaid)

***

### message?

> `optional` **message**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12256](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12256)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`message`](../interfaces/IMarketingMessageAction.md#message)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12255](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12255)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`name`](../interfaces/IMarketingMessageAction.md#name)

***

### type?

> `optional` **type**: `null` \| [`PERSONALIZED`](../namespaces/MarketingMessageAction/enumerations/MarketingMessagePrototypeType.md#personalized)

Defined in: [WAProto/index.d.ts:12257](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12257)

#### Implementation of

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md).[`type`](../interfaces/IMarketingMessageAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12267](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12267)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:12262](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12262)

#### Parameters

##### properties?

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:12264](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12264)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12263](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12263)

#### Parameters

##### m

[`IMarketingMessageAction`](../interfaces/IMarketingMessageAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MarketingMessageAction`](MarketingMessageAction.md)

Defined in: [WAProto/index.d.ts:12265](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12265)

#### Parameters

##### d

#### Returns

[`MarketingMessageAction`](MarketingMessageAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12268](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12268)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12266](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12266)

#### Parameters

##### m

[`MarketingMessageAction`](MarketingMessageAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
