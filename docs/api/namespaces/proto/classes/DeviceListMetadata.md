# Class: DeviceListMetadata

Defined in: [WAProto/index.d.ts:3848](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3848)

## Implements

- [`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

## Constructors

### new DeviceListMetadata()

> **new DeviceListMetadata**(`p`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:3849](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3849)

#### Parameters

##### p?

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

## Properties

### receiverAccountType?

> `optional` **receiverAccountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:3854](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3854)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`receiverAccountType`](../interfaces/IDeviceListMetadata.md#receiveraccounttype)

***

### recipientKeyHash?

> `optional` **recipientKeyHash**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3855](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3855)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientKeyHash`](../interfaces/IDeviceListMetadata.md#recipientkeyhash)

***

### recipientKeyIndexes

> **recipientKeyIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:3857](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3857)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientKeyIndexes`](../interfaces/IDeviceListMetadata.md#recipientkeyindexes)

***

### recipientTimestamp?

> `optional` **recipientTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3856](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3856)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`recipientTimestamp`](../interfaces/IDeviceListMetadata.md#recipienttimestamp)

***

### senderAccountType?

> `optional` **senderAccountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:3853](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3853)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderAccountType`](../interfaces/IDeviceListMetadata.md#senderaccounttype)

***

### senderKeyHash?

> `optional` **senderKeyHash**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3850](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3850)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderKeyHash`](../interfaces/IDeviceListMetadata.md#senderkeyhash)

***

### senderKeyIndexes

> **senderKeyIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:3852](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3852)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderKeyIndexes`](../interfaces/IDeviceListMetadata.md#senderkeyindexes)

***

### senderTimestamp?

> `optional` **senderTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3851](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3851)

#### Implementation of

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md).[`senderTimestamp`](../interfaces/IDeviceListMetadata.md#sendertimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3863](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3863)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:3858](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3858)

#### Parameters

##### properties?

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:3860](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3860)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3859](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3859)

#### Parameters

##### m

[`IDeviceListMetadata`](../interfaces/IDeviceListMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeviceListMetadata`](DeviceListMetadata.md)

Defined in: [WAProto/index.d.ts:3861](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3861)

#### Parameters

##### d

#### Returns

[`DeviceListMetadata`](DeviceListMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3864](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3864)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3862](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3862)

#### Parameters

##### m

[`DeviceListMetadata`](DeviceListMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
