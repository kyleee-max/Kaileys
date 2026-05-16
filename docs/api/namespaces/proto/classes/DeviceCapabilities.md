# Class: DeviceCapabilities

Defined in: [WAProto/index.d.ts:3740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3740)

## Implements

- [`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md)

## Constructors

### new DeviceCapabilities()

> **new DeviceCapabilities**(`p`?): [`DeviceCapabilities`](DeviceCapabilities.md)

Defined in: [WAProto/index.d.ts:3741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3741)

#### Parameters

##### p?

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md)

#### Returns

[`DeviceCapabilities`](DeviceCapabilities.md)

## Properties

### businessBroadcast?

> `optional` **businessBroadcast**: `null` \| [`IBusinessBroadcast`](../namespaces/DeviceCapabilities/interfaces/IBusinessBroadcast.md)

Defined in: [WAProto/index.d.ts:3744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3744)

#### Implementation of

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md).[`businessBroadcast`](../interfaces/IDeviceCapabilities.md#businessbroadcast)

***

### chatLockSupportLevel?

> `optional` **chatLockSupportLevel**: `null` \| [`ChatLockSupportLevel`](../namespaces/DeviceCapabilities/enumerations/ChatLockSupportLevel.md)

Defined in: [WAProto/index.d.ts:3742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3742)

#### Implementation of

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md).[`chatLockSupportLevel`](../interfaces/IDeviceCapabilities.md#chatlocksupportlevel)

***

### lidMigration?

> `optional` **lidMigration**: `null` \| [`ILIDMigration`](../namespaces/DeviceCapabilities/interfaces/ILIDMigration.md)

Defined in: [WAProto/index.d.ts:3743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3743)

#### Implementation of

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md).[`lidMigration`](../interfaces/IDeviceCapabilities.md#lidmigration)

***

### memberNameTagPrimarySupport?

> `optional` **memberNameTagPrimarySupport**: `null` \| [`MemberNameTagPrimarySupport`](../namespaces/DeviceCapabilities/enumerations/MemberNameTagPrimarySupport.md)

Defined in: [WAProto/index.d.ts:3746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3746)

#### Implementation of

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md).[`memberNameTagPrimarySupport`](../interfaces/IDeviceCapabilities.md#membernametagprimarysupport)

***

### userHasAvatar?

> `optional` **userHasAvatar**: `null` \| [`IUserHasAvatar`](../namespaces/DeviceCapabilities/interfaces/IUserHasAvatar.md)

Defined in: [WAProto/index.d.ts:3745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3745)

#### Implementation of

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md).[`userHasAvatar`](../interfaces/IDeviceCapabilities.md#userhasavatar)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3752](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3752)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeviceCapabilities`](DeviceCapabilities.md)

Defined in: [WAProto/index.d.ts:3747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3747)

#### Parameters

##### properties?

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md)

#### Returns

[`DeviceCapabilities`](DeviceCapabilities.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeviceCapabilities`](DeviceCapabilities.md)

Defined in: [WAProto/index.d.ts:3749](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3749)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeviceCapabilities`](DeviceCapabilities.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3748](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3748)

#### Parameters

##### m

[`IDeviceCapabilities`](../interfaces/IDeviceCapabilities.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeviceCapabilities`](DeviceCapabilities.md)

Defined in: [WAProto/index.d.ts:3750](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3750)

#### Parameters

##### d

#### Returns

[`DeviceCapabilities`](DeviceCapabilities.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3753](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3753)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3751](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3751)

#### Parameters

##### m

[`DeviceCapabilities`](DeviceCapabilities.md)

##### o?

`IConversionOptions`

#### Returns

`object`
