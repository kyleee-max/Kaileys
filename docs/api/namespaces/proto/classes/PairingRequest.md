# Class: PairingRequest

Defined in: [WAProto/index.d.ts:10014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10014)

## Implements

- [`IPairingRequest`](../interfaces/IPairingRequest.md)

## Constructors

### new PairingRequest()

> **new PairingRequest**(`p`?): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:10015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10015)

#### Parameters

##### p?

[`IPairingRequest`](../interfaces/IPairingRequest.md)

#### Returns

[`PairingRequest`](PairingRequest.md)

## Properties

### advSecret?

> `optional` **advSecret**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10018)

#### Implementation of

[`IPairingRequest`](../interfaces/IPairingRequest.md).[`advSecret`](../interfaces/IPairingRequest.md#advsecret)

***

### companionIdentityKey?

> `optional` **companionIdentityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10017)

#### Implementation of

[`IPairingRequest`](../interfaces/IPairingRequest.md).[`companionIdentityKey`](../interfaces/IPairingRequest.md#companionidentitykey)

***

### companionPublicKey?

> `optional` **companionPublicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10016)

#### Implementation of

[`IPairingRequest`](../interfaces/IPairingRequest.md).[`companionPublicKey`](../interfaces/IPairingRequest.md#companionpublickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10024)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:10019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10019)

#### Parameters

##### properties?

[`IPairingRequest`](../interfaces/IPairingRequest.md)

#### Returns

[`PairingRequest`](PairingRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:10021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10021)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PairingRequest`](PairingRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10020)

#### Parameters

##### m

[`IPairingRequest`](../interfaces/IPairingRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PairingRequest`](PairingRequest.md)

Defined in: [WAProto/index.d.ts:10022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10022)

#### Parameters

##### d

#### Returns

[`PairingRequest`](PairingRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10025)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10023)

#### Parameters

##### m

[`PairingRequest`](PairingRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
