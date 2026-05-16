# Class: ADVDeviceIdentity

Defined in: [WAProto/index.d.ts:13](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13)

## Implements

- [`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

## Constructors

### new ADVDeviceIdentity()

> **new ADVDeviceIdentity**(`p`?): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:14](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14)

#### Parameters

##### p?

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

## Properties

### accountType?

> `optional` **accountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:18](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L18)

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`accountType`](../interfaces/IADVDeviceIdentity.md#accounttype)

***

### deviceType?

> `optional` **deviceType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:19](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L19)

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`deviceType`](../interfaces/IADVDeviceIdentity.md#devicetype)

***

### keyIndex?

> `optional` **keyIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:17](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L17)

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`keyIndex`](../interfaces/IADVDeviceIdentity.md#keyindex)

***

### rawId?

> `optional` **rawId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:15](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L15)

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`rawId`](../interfaces/IADVDeviceIdentity.md#rawid)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:16](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L16)

#### Implementation of

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md).[`timestamp`](../interfaces/IADVDeviceIdentity.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:25](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L25)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:20](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L20)

#### Parameters

##### properties?

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:22](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L22)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:21](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L21)

#### Parameters

##### m

[`IADVDeviceIdentity`](../interfaces/IADVDeviceIdentity.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ADVDeviceIdentity`](ADVDeviceIdentity.md)

Defined in: [WAProto/index.d.ts:23](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L23)

#### Parameters

##### d

#### Returns

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:26](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L26)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:24](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L24)

#### Parameters

##### m

[`ADVDeviceIdentity`](ADVDeviceIdentity.md)

##### o?

`IConversionOptions`

#### Returns

`object`
