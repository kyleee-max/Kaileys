# Class: BotPromotionMessageMetadata

Defined in: [WAProto/index.d.ts:1904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1904)

## Implements

- [`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

## Constructors

### new BotPromotionMessageMetadata()

> **new BotPromotionMessageMetadata**(`p`?): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:1905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1905)

#### Parameters

##### p?

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

## Properties

### buttonTitle?

> `optional` **buttonTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1907)

#### Implementation of

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md).[`buttonTitle`](../interfaces/IBotPromotionMessageMetadata.md#buttontitle)

***

### promotionType?

> `optional` **promotionType**: `null` \| [`BotPromotionType`](../namespaces/BotPromotionMessageMetadata/enumerations/BotPromotionType.md)

Defined in: [WAProto/index.d.ts:1906](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1906)

#### Implementation of

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md).[`promotionType`](../interfaces/IBotPromotionMessageMetadata.md#promotiontype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1913](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1913)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:1908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1908)

#### Parameters

##### properties?

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:1910](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1910)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1909](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1909)

#### Parameters

##### m

[`IBotPromotionMessageMetadata`](../interfaces/IBotPromotionMessageMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

Defined in: [WAProto/index.d.ts:1911](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1911)

#### Parameters

##### d

#### Returns

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1914)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1912](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1912)

#### Parameters

##### m

[`BotPromotionMessageMetadata`](BotPromotionMessageMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
