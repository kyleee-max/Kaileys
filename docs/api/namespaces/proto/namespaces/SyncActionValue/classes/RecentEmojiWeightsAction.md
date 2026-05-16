# Class: RecentEmojiWeightsAction

Defined in: [WAProto/index.d.ts:12674](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12674)

## Implements

- [`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

## Constructors

### new RecentEmojiWeightsAction()

> **new RecentEmojiWeightsAction**(`p`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:12675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12675)

#### Parameters

##### p?

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

## Properties

### weights

> **weights**: [`IRecentEmojiWeight`](../../../interfaces/IRecentEmojiWeight.md)[]

Defined in: [WAProto/index.d.ts:12676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12676)

#### Implementation of

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md).[`weights`](../interfaces/IRecentEmojiWeightsAction.md#weights)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12682)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:12677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12677)

#### Parameters

##### properties?

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:12679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12679)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12678)

#### Parameters

##### m

[`IRecentEmojiWeightsAction`](../interfaces/IRecentEmojiWeightsAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

Defined in: [WAProto/index.d.ts:12680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12680)

#### Parameters

##### d

#### Returns

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12683](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12683)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12681)

#### Parameters

##### m

[`RecentEmojiWeightsAction`](RecentEmojiWeightsAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
