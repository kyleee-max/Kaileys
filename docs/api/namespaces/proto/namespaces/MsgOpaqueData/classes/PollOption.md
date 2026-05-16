# Class: PollOption

Defined in: [WAProto/index.d.ts:9768](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9768)

## Implements

- [`IPollOption`](../interfaces/IPollOption.md)

## Constructors

### new PollOption()

> **new PollOption**(`p`?): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:9769](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9769)

#### Parameters

##### p?

[`IPollOption`](../interfaces/IPollOption.md)

#### Returns

[`PollOption`](PollOption.md)

## Properties

### hash?

> `optional` **hash**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9771)

#### Implementation of

[`IPollOption`](../interfaces/IPollOption.md).[`hash`](../interfaces/IPollOption.md#hash)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9770](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9770)

#### Implementation of

[`IPollOption`](../interfaces/IPollOption.md).[`name`](../interfaces/IPollOption.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9777](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9777)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:9772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9772)

#### Parameters

##### properties?

[`IPollOption`](../interfaces/IPollOption.md)

#### Returns

[`PollOption`](PollOption.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:9774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9774)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollOption`](PollOption.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9773)

#### Parameters

##### m

[`IPollOption`](../interfaces/IPollOption.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollOption`](PollOption.md)

Defined in: [WAProto/index.d.ts:9775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9775)

#### Parameters

##### d

#### Returns

[`PollOption`](PollOption.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9778](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9778)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9776)

#### Parameters

##### m

[`PollOption`](PollOption.md)

##### o?

`IConversionOptions`

#### Returns

`object`
