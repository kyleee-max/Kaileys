# Class: HydratedQuickReplyButton

Defined in: [WAProto/index.d.ts:4649](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4649)

## Implements

- [`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

## Constructors

### new HydratedQuickReplyButton()

> **new HydratedQuickReplyButton**(`p`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:4650](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4650)

#### Parameters

##### p?

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4651](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4651)

#### Implementation of

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md).[`displayText`](../interfaces/IHydratedQuickReplyButton.md#displaytext)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4652](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4652)

#### Implementation of

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md).[`id`](../interfaces/IHydratedQuickReplyButton.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4658)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:4653](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4653)

#### Parameters

##### properties?

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:4655](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4655)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4654](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4654)

#### Parameters

##### m

[`IHydratedQuickReplyButton`](../interfaces/IHydratedQuickReplyButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:4656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4656)

#### Parameters

##### d

#### Returns

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4659)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4657)

#### Parameters

##### m

[`HydratedQuickReplyButton`](HydratedQuickReplyButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
