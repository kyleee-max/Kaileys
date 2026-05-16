# Class: UserReceipt

Defined in: [WAProto/index.d.ts:13405](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13405)

## Implements

- [`IUserReceipt`](../interfaces/IUserReceipt.md)

## Constructors

### new UserReceipt()

> **new UserReceipt**(`p`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:13406](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13406)

#### Parameters

##### p?

[`IUserReceipt`](../interfaces/IUserReceipt.md)

#### Returns

[`UserReceipt`](UserReceipt.md)

## Properties

### deliveredDeviceJid

> **deliveredDeviceJid**: `string`[]

Defined in: [WAProto/index.d.ts:13412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13412)

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`deliveredDeviceJid`](../interfaces/IUserReceipt.md#delivereddevicejid)

***

### pendingDeviceJid

> **pendingDeviceJid**: `string`[]

Defined in: [WAProto/index.d.ts:13411](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13411)

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`pendingDeviceJid`](../interfaces/IUserReceipt.md#pendingdevicejid)

***

### playedTimestamp?

> `optional` **playedTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13410](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13410)

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`playedTimestamp`](../interfaces/IUserReceipt.md#playedtimestamp)

***

### readTimestamp?

> `optional` **readTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13409](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13409)

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`readTimestamp`](../interfaces/IUserReceipt.md#readtimestamp)

***

### receiptTimestamp?

> `optional` **receiptTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13408](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13408)

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`receiptTimestamp`](../interfaces/IUserReceipt.md#receipttimestamp)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:13407](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13407)

#### Implementation of

[`IUserReceipt`](../interfaces/IUserReceipt.md).[`userJid`](../interfaces/IUserReceipt.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13418)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:13413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13413)

#### Parameters

##### properties?

[`IUserReceipt`](../interfaces/IUserReceipt.md)

#### Returns

[`UserReceipt`](UserReceipt.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:13415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13415)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UserReceipt`](UserReceipt.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13414)

#### Parameters

##### m

[`IUserReceipt`](../interfaces/IUserReceipt.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UserReceipt`](UserReceipt.md)

Defined in: [WAProto/index.d.ts:13416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13416)

#### Parameters

##### d

#### Returns

[`UserReceipt`](UserReceipt.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13419)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13417)

#### Parameters

##### m

[`UserReceipt`](UserReceipt.md)

##### o?

`IConversionOptions`

#### Returns

`object`
