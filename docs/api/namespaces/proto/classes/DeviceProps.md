# Class: DeviceProps

Defined in: [WAProto/index.d.ts:3875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3875)

## Implements

- [`IDeviceProps`](../interfaces/IDeviceProps.md)

## Constructors

### new DeviceProps()

> **new DeviceProps**(`p`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:3876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3876)

#### Parameters

##### p?

[`IDeviceProps`](../interfaces/IDeviceProps.md)

#### Returns

[`DeviceProps`](DeviceProps.md)

## Properties

### historySyncConfig?

> `optional` **historySyncConfig**: `null` \| [`IHistorySyncConfig`](../namespaces/DeviceProps/interfaces/IHistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:3881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3881)

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`historySyncConfig`](../interfaces/IDeviceProps.md#historysyncconfig)

***

### os?

> `optional` **os**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3877)

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`os`](../interfaces/IDeviceProps.md#os)

***

### platformType?

> `optional` **platformType**: `null` \| [`PlatformType`](../namespaces/DeviceProps/enumerations/PlatformType.md)

Defined in: [WAProto/index.d.ts:3879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3879)

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`platformType`](../interfaces/IDeviceProps.md#platformtype)

***

### requireFullSync?

> `optional` **requireFullSync**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3880)

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`requireFullSync`](../interfaces/IDeviceProps.md#requirefullsync)

***

### version?

> `optional` **version**: `null` \| [`IAppVersion`](../namespaces/DeviceProps/interfaces/IAppVersion.md)

Defined in: [WAProto/index.d.ts:3878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3878)

#### Implementation of

[`IDeviceProps`](../interfaces/IDeviceProps.md).[`version`](../interfaces/IDeviceProps.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3887](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3887)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:3882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3882)

#### Parameters

##### properties?

[`IDeviceProps`](../interfaces/IDeviceProps.md)

#### Returns

[`DeviceProps`](DeviceProps.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:3884](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3884)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeviceProps`](DeviceProps.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3883)

#### Parameters

##### m

[`IDeviceProps`](../interfaces/IDeviceProps.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeviceProps`](DeviceProps.md)

Defined in: [WAProto/index.d.ts:3885](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3885)

#### Parameters

##### d

#### Returns

[`DeviceProps`](DeviceProps.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3888](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3888)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3886](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3886)

#### Parameters

##### m

[`DeviceProps`](DeviceProps.md)

##### o?

`IConversionOptions`

#### Returns

`object`
