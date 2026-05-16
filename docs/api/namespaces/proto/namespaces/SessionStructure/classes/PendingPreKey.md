# Class: PendingPreKey

Defined in: [WAProto/index.d.ts:11015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11015)

## Implements

- [`IPendingPreKey`](../interfaces/IPendingPreKey.md)

## Constructors

### new PendingPreKey()

> **new PendingPreKey**(`p`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:11016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11016)

#### Parameters

##### p?

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

#### Returns

[`PendingPreKey`](PendingPreKey.md)

## Properties

### baseKey?

> `optional` **baseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11019)

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`baseKey`](../interfaces/IPendingPreKey.md#basekey)

***

### preKeyId?

> `optional` **preKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11017)

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`preKeyId`](../interfaces/IPendingPreKey.md#prekeyid)

***

### signedPreKeyId?

> `optional` **signedPreKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11018)

#### Implementation of

[`IPendingPreKey`](../interfaces/IPendingPreKey.md).[`signedPreKeyId`](../interfaces/IPendingPreKey.md#signedprekeyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11025)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:11020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11020)

#### Parameters

##### properties?

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

#### Returns

[`PendingPreKey`](PendingPreKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:11022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11022)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PendingPreKey`](PendingPreKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11021)

#### Parameters

##### m

[`IPendingPreKey`](../interfaces/IPendingPreKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PendingPreKey`](PendingPreKey.md)

Defined in: [WAProto/index.d.ts:11023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11023)

#### Parameters

##### d

#### Returns

[`PendingPreKey`](PendingPreKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11026](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11026)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11024)

#### Parameters

##### m

[`PendingPreKey`](PendingPreKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
