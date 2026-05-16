# Class: StatusNotificationMessage

Defined in: [WAProto/index.d.ts:8890](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8890)

## Implements

- [`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

## Constructors

### new StatusNotificationMessage()

> **new StatusNotificationMessage**(`p`?): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:8891](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8891)

#### Parameters

##### p?

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

## Properties

### originalMessageKey?

> `optional` **originalMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8893](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8893)

#### Implementation of

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md).[`originalMessageKey`](../interfaces/IStatusNotificationMessage.md#originalmessagekey)

***

### responseMessageKey?

> `optional` **responseMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8892](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8892)

#### Implementation of

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md).[`responseMessageKey`](../interfaces/IStatusNotificationMessage.md#responsemessagekey)

***

### type?

> `optional` **type**: `null` \| [`StatusNotificationType`](../namespaces/StatusNotificationMessage/enumerations/StatusNotificationType.md)

Defined in: [WAProto/index.d.ts:8894](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8894)

#### Implementation of

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md).[`type`](../interfaces/IStatusNotificationMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8900)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:8895](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8895)

#### Parameters

##### properties?

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:8897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8897)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8896)

#### Parameters

##### m

[`IStatusNotificationMessage`](../interfaces/IStatusNotificationMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusNotificationMessage`](StatusNotificationMessage.md)

Defined in: [WAProto/index.d.ts:8898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8898)

#### Parameters

##### d

#### Returns

[`StatusNotificationMessage`](StatusNotificationMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8901)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8899)

#### Parameters

##### m

[`StatusNotificationMessage`](StatusNotificationMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
