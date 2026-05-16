# Class: ADVSignedDeviceIdentityHMAC

Defined in: [WAProto/index.d.ts:86](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L86)

## Implements

- [`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

## Constructors

### new ADVSignedDeviceIdentityHMAC()

> **new ADVSignedDeviceIdentityHMAC**(`p`?): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:87](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L87)

#### Parameters

##### p?

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

## Properties

### accountType?

> `optional` **accountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:90](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L90)

#### Implementation of

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md).[`accountType`](../interfaces/IADVSignedDeviceIdentityHMAC.md#accounttype)

***

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:88](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L88)

#### Implementation of

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md).[`details`](../interfaces/IADVSignedDeviceIdentityHMAC.md#details)

***

### hmac?

> `optional` **hmac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:89](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L89)

#### Implementation of

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md).[`hmac`](../interfaces/IADVSignedDeviceIdentityHMAC.md#hmac)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:96](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L96)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:91](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L91)

#### Parameters

##### properties?

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:93](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L93)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:92](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L92)

#### Parameters

##### m

[`IADVSignedDeviceIdentityHMAC`](../interfaces/IADVSignedDeviceIdentityHMAC.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

Defined in: [WAProto/index.d.ts:94](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L94)

#### Parameters

##### d

#### Returns

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:97](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L97)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:95](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L95)

#### Parameters

##### m

[`ADVSignedDeviceIdentityHMAC`](ADVSignedDeviceIdentityHMAC.md)

##### o?

`IConversionOptions`

#### Returns

`object`
