# Class: ADVSignedDeviceIdentity

Defined in: [WAProto/index.d.ts:65](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L65)

## Implements

- [`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

## Constructors

### new ADVSignedDeviceIdentity()

> **new ADVSignedDeviceIdentity**(`p`?): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:66](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L66)

#### Parameters

##### p?

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

## Properties

### accountSignature?

> `optional` **accountSignature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:69](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L69)

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`accountSignature`](../interfaces/IADVSignedDeviceIdentity.md#accountsignature)

***

### accountSignatureKey?

> `optional` **accountSignatureKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:68](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L68)

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`accountSignatureKey`](../interfaces/IADVSignedDeviceIdentity.md#accountsignaturekey)

***

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:67](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L67)

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`details`](../interfaces/IADVSignedDeviceIdentity.md#details)

***

### deviceSignature?

> `optional` **deviceSignature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:70](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L70)

#### Implementation of

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md).[`deviceSignature`](../interfaces/IADVSignedDeviceIdentity.md#devicesignature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:76](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L76)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:71](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L71)

#### Parameters

##### properties?

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:73](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L73)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:72](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L72)

#### Parameters

##### m

[`IADVSignedDeviceIdentity`](../interfaces/IADVSignedDeviceIdentity.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:74](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L74)

#### Parameters

##### d

#### Returns

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:77](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L77)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:75](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L75)

#### Parameters

##### m

[`ADVSignedDeviceIdentity`](ADVSignedDeviceIdentity.md)

##### o?

`IConversionOptions`

#### Returns

`object`
