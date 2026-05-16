# Class: CloudAPIThreadControlNotificationContent

Defined in: [WAProto/index.d.ts:5925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5925)

## Implements

- [`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

## Constructors

### new CloudAPIThreadControlNotificationContent()

> **new CloudAPIThreadControlNotificationContent**(`p`?): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:5926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5926)

#### Parameters

##### p?

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

## Properties

### extraJson?

> `optional` **extraJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5928)

#### Implementation of

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md).[`extraJson`](../interfaces/ICloudAPIThreadControlNotificationContent.md#extrajson)

***

### handoffNotificationText?

> `optional` **handoffNotificationText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5927)

#### Implementation of

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md).[`handoffNotificationText`](../interfaces/ICloudAPIThreadControlNotificationContent.md#handoffnotificationtext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5934)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:5929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5929)

#### Parameters

##### properties?

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:5931](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5931)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5930](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5930)

#### Parameters

##### m

[`ICloudAPIThreadControlNotificationContent`](../interfaces/ICloudAPIThreadControlNotificationContent.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:5932](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5932)

#### Parameters

##### d

#### Returns

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5935)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5933)

#### Parameters

##### m

[`CloudAPIThreadControlNotificationContent`](CloudAPIThreadControlNotificationContent.md)

##### o?

`IConversionOptions`

#### Returns

`object`
