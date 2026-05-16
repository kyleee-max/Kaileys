# Class: NotificationSettings

Defined in: [WAProto/index.d.ts:9991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9991)

## Implements

- [`INotificationSettings`](../interfaces/INotificationSettings.md)

## Constructors

### new NotificationSettings()

> **new NotificationSettings**(`p`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:9992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9992)

#### Parameters

##### p?

[`INotificationSettings`](../interfaces/INotificationSettings.md)

#### Returns

[`NotificationSettings`](NotificationSettings.md)

## Properties

### callVibrate?

> `optional` **callVibrate**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9998](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9998)

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`callVibrate`](../interfaces/INotificationSettings.md#callvibrate)

***

### lowPriorityNotifications?

> `optional` **lowPriorityNotifications**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9996](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9996)

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`lowPriorityNotifications`](../interfaces/INotificationSettings.md#lowprioritynotifications)

***

### messageLight?

> `optional` **messageLight**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9995)

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messageLight`](../interfaces/INotificationSettings.md#messagelight)

***

### messagePopup?

> `optional` **messagePopup**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9994)

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messagePopup`](../interfaces/INotificationSettings.md#messagepopup)

***

### messageVibrate?

> `optional` **messageVibrate**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9993](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9993)

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`messageVibrate`](../interfaces/INotificationSettings.md#messagevibrate)

***

### reactionsMuted?

> `optional` **reactionsMuted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9997](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9997)

#### Implementation of

[`INotificationSettings`](../interfaces/INotificationSettings.md).[`reactionsMuted`](../interfaces/INotificationSettings.md#reactionsmuted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10004](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10004)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:9999](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9999)

#### Parameters

##### properties?

[`INotificationSettings`](../interfaces/INotificationSettings.md)

#### Returns

[`NotificationSettings`](NotificationSettings.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:10001](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10001)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NotificationSettings`](NotificationSettings.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10000](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10000)

#### Parameters

##### m

[`INotificationSettings`](../interfaces/INotificationSettings.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NotificationSettings`](NotificationSettings.md)

Defined in: [WAProto/index.d.ts:10002](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10002)

#### Parameters

##### d

#### Returns

[`NotificationSettings`](NotificationSettings.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10005)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10003)

#### Parameters

##### m

[`NotificationSettings`](NotificationSettings.md)

##### o?

`IConversionOptions`

#### Returns

`object`
