# Class: NoiseCertificate

Defined in: [WAProto/index.d.ts:9920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9920)

## Implements

- [`INoiseCertificate`](../interfaces/INoiseCertificate.md)

## Constructors

### new NoiseCertificate()

> **new NoiseCertificate**(`p`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:9921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9921)

#### Parameters

##### p?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

## Properties

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9922](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9922)

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`details`](../interfaces/INoiseCertificate.md#details)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9923)

#### Implementation of

[`INoiseCertificate`](../interfaces/INoiseCertificate.md).[`signature`](../interfaces/INoiseCertificate.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9929)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:9924](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9924)

#### Parameters

##### properties?

[`INoiseCertificate`](../interfaces/INoiseCertificate.md)

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NoiseCertificate`](NoiseCertificate.md)

Defined in: [WAProto/index.d.ts:9926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9926)

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

Defined in: [WAProto/index.d.ts:9925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9925)

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

Defined in: [WAProto/index.d.ts:9927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9927)

#### Parameters

##### d

#### Returns

[`NoiseCertificate`](NoiseCertificate.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9930](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9930)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9928)

#### Parameters

##### m

[`NoiseCertificate`](NoiseCertificate.md)

##### o?

`IConversionOptions`

#### Returns

`object`
