# Class: PollEncValue

Defined in: [WAProto/index.d.ts:10406](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10406)

## Implements

- [`IPollEncValue`](../interfaces/IPollEncValue.md)

## Constructors

### new PollEncValue()

> **new PollEncValue**(`p`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:10407](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10407)

#### Parameters

##### p?

[`IPollEncValue`](../interfaces/IPollEncValue.md)

#### Returns

[`PollEncValue`](PollEncValue.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10409](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10409)

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encIv`](../interfaces/IPollEncValue.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10408](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10408)

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encPayload`](../interfaces/IPollEncValue.md#encpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10415)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:10410](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10410)

#### Parameters

##### properties?

[`IPollEncValue`](../interfaces/IPollEncValue.md)

#### Returns

[`PollEncValue`](PollEncValue.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:10412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10412)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollEncValue`](PollEncValue.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10411](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10411)

#### Parameters

##### m

[`IPollEncValue`](../interfaces/IPollEncValue.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:10413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10413)

#### Parameters

##### d

#### Returns

[`PollEncValue`](PollEncValue.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10416)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10414)

#### Parameters

##### m

[`PollEncValue`](PollEncValue.md)

##### o?

`IConversionOptions`

#### Returns

`object`
