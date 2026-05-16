# Class: CloudAPIThreadControlNotification

Defined in: [WAProto/index.d.ts:5895](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5895)

## Implements

- [`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

## Constructors

### new CloudAPIThreadControlNotification()

> **new CloudAPIThreadControlNotification**(`p`?): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:5896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5896)

#### Parameters

##### p?

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

## Properties

### consumerLid?

> `optional` **consumerLid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5899)

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`consumerLid`](../interfaces/ICloudAPIThreadControlNotification.md#consumerlid)

***

### consumerPhoneNumber?

> `optional` **consumerPhoneNumber**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5900)

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`consumerPhoneNumber`](../interfaces/ICloudAPIThreadControlNotification.md#consumerphonenumber)

***

### notificationContent?

> `optional` **notificationContent**: `null` \| [`ICloudAPIThreadControlNotificationContent`](../namespaces/CloudAPIThreadControlNotification/interfaces/ICloudAPIThreadControlNotificationContent.md)

Defined in: [WAProto/index.d.ts:5901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5901)

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`notificationContent`](../interfaces/ICloudAPIThreadControlNotification.md#notificationcontent)

***

### senderNotificationTimestampMs?

> `optional` **senderNotificationTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5898)

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`senderNotificationTimestampMs`](../interfaces/ICloudAPIThreadControlNotification.md#sendernotificationtimestampms)

***

### shouldSuppressNotification?

> `optional` **shouldSuppressNotification**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:5902](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5902)

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`shouldSuppressNotification`](../interfaces/ICloudAPIThreadControlNotification.md#shouldsuppressnotification)

***

### status?

> `optional` **status**: `null` \| [`CloudAPIThreadControl`](../namespaces/CloudAPIThreadControlNotification/enumerations/CloudAPIThreadControl.md)

Defined in: [WAProto/index.d.ts:5897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5897)

#### Implementation of

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md).[`status`](../interfaces/ICloudAPIThreadControlNotification.md#status)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5908)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:5903](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5903)

#### Parameters

##### properties?

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:5905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5905)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5904)

#### Parameters

##### m

[`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:5906](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5906)

#### Parameters

##### d

#### Returns

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5909](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5909)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5907)

#### Parameters

##### m

[`CloudAPIThreadControlNotification`](CloudAPIThreadControlNotification.md)

##### o?

`IConversionOptions`

#### Returns

`object`
