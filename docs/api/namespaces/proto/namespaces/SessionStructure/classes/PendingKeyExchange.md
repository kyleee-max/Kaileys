# Class: PendingKeyExchange

Defined in: [WAProto/index.d.ts:10991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10991)

## Implements

- [`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

## Constructors

### new PendingKeyExchange()

> **new PendingKeyExchange**(`p`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:10992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10992)

#### Parameters

##### p?

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

## Properties

### localBaseKey?

> `optional` **localBaseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10994)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localBaseKey`](../interfaces/IPendingKeyExchange.md#localbasekey)

***

### localBaseKeyPrivate?

> `optional` **localBaseKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10995)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localBaseKeyPrivate`](../interfaces/IPendingKeyExchange.md#localbasekeyprivate)

***

### localIdentityKey?

> `optional` **localIdentityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10998](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10998)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localIdentityKey`](../interfaces/IPendingKeyExchange.md#localidentitykey)

***

### localIdentityKeyPrivate?

> `optional` **localIdentityKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10999](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10999)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localIdentityKeyPrivate`](../interfaces/IPendingKeyExchange.md#localidentitykeyprivate)

***

### localRatchetKey?

> `optional` **localRatchetKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10996](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10996)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localRatchetKey`](../interfaces/IPendingKeyExchange.md#localratchetkey)

***

### localRatchetKeyPrivate?

> `optional` **localRatchetKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10997](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10997)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`localRatchetKeyPrivate`](../interfaces/IPendingKeyExchange.md#localratchetkeyprivate)

***

### sequence?

> `optional` **sequence**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10993](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10993)

#### Implementation of

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md).[`sequence`](../interfaces/IPendingKeyExchange.md#sequence)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11005)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:11000](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11000)

#### Parameters

##### properties?

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:11002](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11002)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11001](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11001)

#### Parameters

##### m

[`IPendingKeyExchange`](../interfaces/IPendingKeyExchange.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PendingKeyExchange`](PendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:11003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11003)

#### Parameters

##### d

#### Returns

[`PendingKeyExchange`](PendingKeyExchange.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11006](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11006)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11004](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11004)

#### Parameters

##### m

[`PendingKeyExchange`](PendingKeyExchange.md)

##### o?

`IConversionOptions`

#### Returns

`object`
