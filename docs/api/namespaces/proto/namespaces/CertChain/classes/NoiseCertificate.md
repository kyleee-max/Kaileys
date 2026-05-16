# Class: NoiseCertificate

Defined in: [WAProto/index.d.ts:2416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2416)

## Implements

- [`INoiseCertificate`](../interfaces/INoiseCertificate.md)

## Constructors

### new NoiseCertificate()

> **new NoiseCertificate**(`p`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2417)

#### Parameters

##### p?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

## Properties

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2418)

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`details`](../interfaces/INoiseCertificate.md#details)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2419)

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`signature`](../interfaces/INoiseCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2425](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2425)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2420)

#### Parameters

##### properties?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2422)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2421)

#### Parameters

##### m

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:2423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2423)

#### Parameters

##### d

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2426](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2426)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2424)

#### Parameters

##### m

[`NoiseCertificate`](NoiseCertificate.md)

##### o?

`IConversionOptions`

#### Returns

`object`
