# Class: BizIdentityInfo

Defined in: [WAProto/index.d.ts:874](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L874)

## Implements

- [`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

## Constructors

### new BizIdentityInfo()

> **new BizIdentityInfo**(`p`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L875)

#### Parameters

##### p?

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

## Properties

### actualActors?

> `optional` **actualActors**: `null` \| [`ActualActorsType`](../namespaces/BizIdentityInfo/enumerations/ActualActorsType.md)

Defined in: [WAProto/index.d.ts:881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L881)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`actualActors`](../interfaces/IBizIdentityInfo.md#actualactors)

***

### featureControls?

> `optional` **featureControls**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L883)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`featureControls`](../interfaces/IBizIdentityInfo.md#featurecontrols)

***

### hostStorage?

> `optional` **hostStorage**: `null` \| [`HostStorageType`](../namespaces/BizIdentityInfo/enumerations/HostStorageType.md)

Defined in: [WAProto/index.d.ts:880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L880)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`hostStorage`](../interfaces/IBizIdentityInfo.md#hoststorage)

***

### privacyModeTs?

> `optional` **privacyModeTs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L882)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`privacyModeTs`](../interfaces/IBizIdentityInfo.md#privacymodets)

***

### revoked?

> `optional` **revoked**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L879)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`revoked`](../interfaces/IBizIdentityInfo.md#revoked)

***

### signed?

> `optional` **signed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L878)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`signed`](../interfaces/IBizIdentityInfo.md#signed)

***

### vlevel?

> `optional` **vlevel**: `null` \| [`VerifiedLevelValue`](../namespaces/BizIdentityInfo/enumerations/VerifiedLevelValue.md)

Defined in: [WAProto/index.d.ts:876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L876)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`vlevel`](../interfaces/IBizIdentityInfo.md#vlevel)

***

### vnameCert?

> `optional` **vnameCert**: `null` \| [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L877)

#### Implementation of

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md).[`vnameCert`](../interfaces/IBizIdentityInfo.md#vnamecert)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:889](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L889)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:884](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L884)

#### Parameters

##### properties?

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:886](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L886)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:885](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L885)

#### Parameters

##### m

[`IBizIdentityInfo`](../interfaces/IBizIdentityInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BizIdentityInfo`](BizIdentityInfo.md)

Defined in: [WAProto/index.d.ts:887](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L887)

#### Parameters

##### d

#### Returns

[`BizIdentityInfo`](BizIdentityInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:890](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L890)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:888](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L888)

#### Parameters

##### m

[`BizIdentityInfo`](BizIdentityInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
