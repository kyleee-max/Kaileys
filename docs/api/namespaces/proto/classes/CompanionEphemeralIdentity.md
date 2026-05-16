# Class: CompanionEphemeralIdentity

Defined in: [WAProto/index.d.ts:3097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3097)

## Implements

- [`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

## Constructors

### new CompanionEphemeralIdentity()

> **new CompanionEphemeralIdentity**(`p`?): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:3098](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3098)

#### Parameters

##### p?

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

## Properties

### deviceType?

> `optional` **deviceType**: `null` \| [`PlatformType`](../namespaces/DeviceProps/enumerations/PlatformType.md)

Defined in: [WAProto/index.d.ts:3100](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3100)

#### Implementation of

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md).[`deviceType`](../interfaces/ICompanionEphemeralIdentity.md#devicetype)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3099](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3099)

#### Implementation of

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md).[`publicKey`](../interfaces/ICompanionEphemeralIdentity.md#publickey)

***

### ref?

> `optional` **ref**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3101](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3101)

#### Implementation of

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md).[`ref`](../interfaces/ICompanionEphemeralIdentity.md#ref)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3107)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:3102](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3102)

#### Parameters

##### properties?

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:3104](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3104)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3103](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3103)

#### Parameters

##### m

[`ICompanionEphemeralIdentity`](../interfaces/ICompanionEphemeralIdentity.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

Defined in: [WAProto/index.d.ts:3105](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3105)

#### Parameters

##### d

#### Returns

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3108](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3108)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3106](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3106)

#### Parameters

##### m

[`CompanionEphemeralIdentity`](CompanionEphemeralIdentity.md)

##### o?

`IConversionOptions`

#### Returns

`object`
