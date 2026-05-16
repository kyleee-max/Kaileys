# Class: VerifiedNameCertificate

Defined in: [WAProto/index.d.ts:13428](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13428)

## Implements

- [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

## Constructors

### new VerifiedNameCertificate()

> **new VerifiedNameCertificate**(`p`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:13429](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13429)

#### Parameters

##### p?

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

## Properties

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13430](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13430)

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`details`](../interfaces/IVerifiedNameCertificate.md#details)

***

### serverSignature?

> `optional` **serverSignature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13432](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13432)

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`serverSignature`](../interfaces/IVerifiedNameCertificate.md#serversignature)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13431](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13431)

#### Implementation of

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md).[`signature`](../interfaces/IVerifiedNameCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13438](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13438)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:13433](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13433)

#### Parameters

##### properties?

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:13435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13435)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13434)

#### Parameters

##### m

[`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`VerifiedNameCertificate`](VerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:13436](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13436)

#### Parameters

##### d

#### Returns

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13439)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13437](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13437)

#### Parameters

##### m

[`VerifiedNameCertificate`](VerifiedNameCertificate.md)

##### o?

`IConversionOptions`

#### Returns

`object`
