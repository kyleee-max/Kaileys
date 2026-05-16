# Class: KeyExpiration

Defined in: [WAProto/index.d.ts:12056](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12056)

## Implements

- [`IKeyExpiration`](../interfaces/IKeyExpiration.md)

## Constructors

### new KeyExpiration()

> **new KeyExpiration**(`p`?): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:12057](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12057)

#### Parameters

##### p?

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

#### Returns

[`KeyExpiration`](KeyExpiration.md)

## Properties

### expiredKeyEpoch?

> `optional` **expiredKeyEpoch**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12058](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12058)

#### Implementation of

[`IKeyExpiration`](../interfaces/IKeyExpiration.md).[`expiredKeyEpoch`](../interfaces/IKeyExpiration.md#expiredkeyepoch)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12064)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:12059](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12059)

#### Parameters

##### properties?

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

#### Returns

[`KeyExpiration`](KeyExpiration.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:12061](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12061)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`KeyExpiration`](KeyExpiration.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12060](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12060)

#### Parameters

##### m

[`IKeyExpiration`](../interfaces/IKeyExpiration.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`KeyExpiration`](KeyExpiration.md)

Defined in: [WAProto/index.d.ts:12062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12062)

#### Parameters

##### d

#### Returns

[`KeyExpiration`](KeyExpiration.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12065)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12063)

#### Parameters

##### m

[`KeyExpiration`](KeyExpiration.md)

##### o?

`IConversionOptions`

#### Returns

`object`
