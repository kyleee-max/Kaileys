# Class: DeviceSentMessage

Defined in: [WAProto/index.d.ts:6019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6019)

## Implements

- [`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

## Constructors

### new DeviceSentMessage()

> **new DeviceSentMessage**(`p`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:6020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6020)

#### Parameters

##### p?

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

## Properties

### destinationJid?

> `optional` **destinationJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6021)

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`destinationJid`](../interfaces/IDeviceSentMessage.md#destinationjid)

***

### message?

> `optional` **message**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:6022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6022)

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`message`](../interfaces/IDeviceSentMessage.md#message)

***

### phash?

> `optional` **phash**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6023)

#### Implementation of

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md).[`phash`](../interfaces/IDeviceSentMessage.md#phash)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6029](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6029)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:6024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6024)

#### Parameters

##### properties?

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:6026](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6026)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6025)

#### Parameters

##### m

[`IDeviceSentMessage`](../interfaces/IDeviceSentMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeviceSentMessage`](DeviceSentMessage.md)

Defined in: [WAProto/index.d.ts:6027](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6027)

#### Parameters

##### d

#### Returns

[`DeviceSentMessage`](DeviceSentMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6030](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6030)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6028](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6028)

#### Parameters

##### m

[`DeviceSentMessage`](DeviceSentMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
