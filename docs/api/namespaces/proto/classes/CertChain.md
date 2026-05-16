# Class: CertChain

Defined in: [WAProto/index.d.ts:2396](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2396)

## Implements

- [`ICertChain`](../interfaces/ICertChain.md)

## Constructors

### new CertChain()

> **new CertChain**(`p`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2397](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2397)

#### Parameters

##### p?

[`ICertChain`](../interfaces/ICertChain.md)

#### Returns

[`CertChain`](CertChain.md)

## Properties

### intermediate?

> `optional` **intermediate**: `null` \| [`INoiseCertificate`](../namespaces/CertChain/interfaces/INoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2399](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2399)

#### Implementation of

[`ICertChain`](../interfaces/ICertChain.md).[`intermediate`](../interfaces/ICertChain.md#intermediate)

***

### leaf?

> `optional` **leaf**: `null` \| [`INoiseCertificate`](../namespaces/CertChain/interfaces/INoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2398](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2398)

#### Implementation of

[`ICertChain`](../interfaces/ICertChain.md).[`leaf`](../interfaces/ICertChain.md#leaf)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2405](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2405)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2400](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2400)

#### Parameters

##### properties?

[`ICertChain`](../interfaces/ICertChain.md)

#### Returns

[`CertChain`](CertChain.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2402](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2402)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CertChain`](CertChain.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2401](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2401)

#### Parameters

##### m

[`ICertChain`](../interfaces/ICertChain.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CertChain`](CertChain.md)

Defined in: [WAProto/index.d.ts:2403](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2403)

#### Parameters

##### d

#### Returns

[`CertChain`](CertChain.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2406](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2406)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2404](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2404)

#### Parameters

##### m

[`CertChain`](CertChain.md)

##### o?

`IConversionOptions`

#### Returns

`object`
