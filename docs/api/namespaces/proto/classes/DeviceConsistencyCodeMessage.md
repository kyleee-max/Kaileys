# Class: DeviceConsistencyCodeMessage

Defined in: [WAProto/index.d.ts:3824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3824)

## Implements

- [`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

## Constructors

### new DeviceConsistencyCodeMessage()

> **new DeviceConsistencyCodeMessage**(`p`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:3825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3825)

#### Parameters

##### p?

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

## Properties

### generation?

> `optional` **generation**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3826)

#### Implementation of

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md).[`generation`](../interfaces/IDeviceConsistencyCodeMessage.md#generation)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3827)

#### Implementation of

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md).[`signature`](../interfaces/IDeviceConsistencyCodeMessage.md#signature)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3833)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:3828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3828)

#### Parameters

##### properties?

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:3830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3830)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3829)

#### Parameters

##### m

[`IDeviceConsistencyCodeMessage`](../interfaces/IDeviceConsistencyCodeMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

Defined in: [WAProto/index.d.ts:3831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3831)

#### Parameters

##### d

#### Returns

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3834)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3832)

#### Parameters

##### m

[`DeviceConsistencyCodeMessage`](DeviceConsistencyCodeMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
