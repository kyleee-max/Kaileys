# Class: RecentEmojiWeight

Defined in: [WAProto/index.d.ts:10652](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10652)

## Implements

- [`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

## Constructors

### new RecentEmojiWeight()

> **new RecentEmojiWeight**(`p`?): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:10653](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10653)

#### Parameters

##### p?

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

## Properties

### emoji?

> `optional` **emoji**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10654](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10654)

#### Implementation of

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md).[`emoji`](../interfaces/IRecentEmojiWeight.md#emoji)

***

### weight?

> `optional` **weight**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10655](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10655)

#### Implementation of

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md).[`weight`](../interfaces/IRecentEmojiWeight.md#weight)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10661)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:10656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10656)

#### Parameters

##### properties?

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:10658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10658)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10657)

#### Parameters

##### m

[`IRecentEmojiWeight`](../interfaces/IRecentEmojiWeight.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RecentEmojiWeight`](RecentEmojiWeight.md)

Defined in: [WAProto/index.d.ts:10659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10659)

#### Parameters

##### d

#### Returns

[`RecentEmojiWeight`](RecentEmojiWeight.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10662](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10662)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10660)

#### Parameters

##### m

[`RecentEmojiWeight`](RecentEmojiWeight.md)

##### o?

`IConversionOptions`

#### Returns

`object`
