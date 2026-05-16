# Class: PrimaryEphemeralIdentity

Defined in: [WAProto/index.d.ts:10510](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10510)

## Implements

- [`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

## Constructors

### new PrimaryEphemeralIdentity()

> **new PrimaryEphemeralIdentity**(`p`?): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10511](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10511)

#### Parameters

##### p?

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

## Properties

### nonce?

> `optional` **nonce**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10513)

#### Implementation of

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md).[`nonce`](../interfaces/IPrimaryEphemeralIdentity.md#nonce)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10512](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10512)

#### Implementation of

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md).[`publicKey`](../interfaces/IPrimaryEphemeralIdentity.md#publickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10519](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10519)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10514](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10514)

#### Parameters

##### properties?

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10516](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10516)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10515](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10515)

#### Parameters

##### m

[`IPrimaryEphemeralIdentity`](../interfaces/IPrimaryEphemeralIdentity.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:10517](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10517)

#### Parameters

##### d

#### Returns

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10520](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10520)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10518](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10518)

#### Parameters

##### m

[`PrimaryEphemeralIdentity`](PrimaryEphemeralIdentity.md)

##### o?

`IConversionOptions`

#### Returns

`object`
