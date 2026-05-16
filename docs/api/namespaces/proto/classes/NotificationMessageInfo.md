# Class: NotificationMessageInfo

Defined in: [WAProto/index.d.ts:9967](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9967)

## Implements

- [`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

## Constructors

### new NotificationMessageInfo()

> **new NotificationMessageInfo**(`p`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:9968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9968)

#### Parameters

##### p?

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:9969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9969)

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`key`](../interfaces/INotificationMessageInfo.md#key)

***

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:9970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9970)

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`message`](../interfaces/INotificationMessageInfo.md#message)

***

### messageTimestamp?

> `optional` **messageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9971)

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`messageTimestamp`](../interfaces/INotificationMessageInfo.md#messagetimestamp)

***

### participant?

> `optional` **participant**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9972)

#### Implementation of

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md).[`participant`](../interfaces/INotificationMessageInfo.md#participant)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9978](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9978)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:9973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9973)

#### Parameters

##### properties?

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:9975](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9975)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9974)

#### Parameters

##### m

[`INotificationMessageInfo`](../interfaces/INotificationMessageInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NotificationMessageInfo`](NotificationMessageInfo.md)

Defined in: [WAProto/index.d.ts:9976](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9976)

#### Parameters

##### d

#### Returns

[`NotificationMessageInfo`](NotificationMessageInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9979](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9979)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9977](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9977)

#### Parameters

##### m

[`NotificationMessageInfo`](NotificationMessageInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
