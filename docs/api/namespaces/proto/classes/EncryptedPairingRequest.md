# Class: EncryptedPairingRequest

Defined in: [WAProto/index.d.ts:4123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4123)

## Implements

- [`IEncryptedPairingRequest`](../interfaces/IEncryptedPairingRequest.md)

## Constructors

### new EncryptedPairingRequest()

> **new EncryptedPairingRequest**(`p`?): [`EncryptedPairingRequest`](EncryptedPairingRequest.md)

Defined in: [WAProto/index.d.ts:4124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4124)

#### Parameters

##### p?

[`IEncryptedPairingRequest`](../interfaces/IEncryptedPairingRequest.md)

#### Returns

[`EncryptedPairingRequest`](EncryptedPairingRequest.md)

## Properties

### encryptedPayload?

> `optional` **encryptedPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4125)

#### Implementation of

[`IEncryptedPairingRequest`](../interfaces/IEncryptedPairingRequest.md).[`encryptedPayload`](../interfaces/IEncryptedPairingRequest.md#encryptedpayload)

***

### iv?

> `optional` **iv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4126)

#### Implementation of

[`IEncryptedPairingRequest`](../interfaces/IEncryptedPairingRequest.md).[`iv`](../interfaces/IEncryptedPairingRequest.md#iv)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4132](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4132)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EncryptedPairingRequest`](EncryptedPairingRequest.md)

Defined in: [WAProto/index.d.ts:4127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4127)

#### Parameters

##### properties?

[`IEncryptedPairingRequest`](../interfaces/IEncryptedPairingRequest.md)

#### Returns

[`EncryptedPairingRequest`](EncryptedPairingRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EncryptedPairingRequest`](EncryptedPairingRequest.md)

Defined in: [WAProto/index.d.ts:4129](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4129)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EncryptedPairingRequest`](EncryptedPairingRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4128](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4128)

#### Parameters

##### m

[`IEncryptedPairingRequest`](../interfaces/IEncryptedPairingRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EncryptedPairingRequest`](EncryptedPairingRequest.md)

Defined in: [WAProto/index.d.ts:4130](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4130)

#### Parameters

##### d

#### Returns

[`EncryptedPairingRequest`](EncryptedPairingRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4133](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4133)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4131](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4131)

#### Parameters

##### m

[`EncryptedPairingRequest`](EncryptedPairingRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
