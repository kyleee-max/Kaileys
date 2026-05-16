# Class: PollEncValue

Defined in: [WAProto/index.d.ts:8356](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8356)

## Implements

- [`IPollEncValue`](../interfaces/IPollEncValue.md)

## Constructors

### new PollEncValue()

> **new PollEncValue**(`p`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:8357](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8357)

#### Parameters

##### p?

[`IPollEncValue`](../interfaces/IPollEncValue.md)

#### Returns

[`PollEncValue`](PollEncValue.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8359](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8359)

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encIv`](../interfaces/IPollEncValue.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8358](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8358)

#### Implementation of

[`IPollEncValue`](../interfaces/IPollEncValue.md).[`encPayload`](../interfaces/IPollEncValue.md#encpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8365](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8365)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:8360](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8360)

#### Parameters

##### properties?

[`IPollEncValue`](../interfaces/IPollEncValue.md)

#### Returns

[`PollEncValue`](PollEncValue.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollEncValue`](PollEncValue.md)

Defined in: [WAProto/index.d.ts:8362](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8362)

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

Defined in: [WAProto/index.d.ts:8361](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8361)

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

Defined in: [WAProto/index.d.ts:8363](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8363)

#### Parameters

##### d

#### Returns

[`PollEncValue`](PollEncValue.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8366](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8366)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8364](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8364)

#### Parameters

##### m

[`PollEncValue`](PollEncValue.md)

##### o?

`IConversionOptions`

#### Returns

`object`
