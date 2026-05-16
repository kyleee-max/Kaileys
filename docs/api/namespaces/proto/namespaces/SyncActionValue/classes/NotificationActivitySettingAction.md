# Class: NotificationActivitySettingAction

Defined in: [WAProto/index.d.ts:12414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12414)

## Implements

- [`INotificationActivitySettingAction`](../interfaces/INotificationActivitySettingAction.md)

## Constructors

### new NotificationActivitySettingAction()

> **new NotificationActivitySettingAction**(`p`?): [`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

Defined in: [WAProto/index.d.ts:12415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12415)

#### Parameters

##### p?

[`INotificationActivitySettingAction`](../interfaces/INotificationActivitySettingAction.md)

#### Returns

[`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

## Properties

### notificationActivitySetting?

> `optional` **notificationActivitySetting**: `null` \| [`NotificationActivitySetting`](../namespaces/NotificationActivitySettingAction/enumerations/NotificationActivitySetting.md)

Defined in: [WAProto/index.d.ts:12416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12416)

#### Implementation of

[`INotificationActivitySettingAction`](../interfaces/INotificationActivitySettingAction.md).[`notificationActivitySetting`](../interfaces/INotificationActivitySettingAction.md#notificationactivitysetting)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12422)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

Defined in: [WAProto/index.d.ts:12417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12417)

#### Parameters

##### properties?

[`INotificationActivitySettingAction`](../interfaces/INotificationActivitySettingAction.md)

#### Returns

[`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

Defined in: [WAProto/index.d.ts:12419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12419)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12418)

#### Parameters

##### m

[`INotificationActivitySettingAction`](../interfaces/INotificationActivitySettingAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

Defined in: [WAProto/index.d.ts:12420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12420)

#### Parameters

##### d

#### Returns

[`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12423)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12421)

#### Parameters

##### m

[`NotificationActivitySettingAction`](NotificationActivitySettingAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
