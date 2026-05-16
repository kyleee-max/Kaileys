# Class: WebNotificationsInfo

Defined in: [WAProto/index.d.ts:14003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14003)

## Implements

- [`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

## Constructors

### new WebNotificationsInfo()

> **new WebNotificationsInfo**(`p`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:14004](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14004)

#### Parameters

##### p?

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

## Properties

### notifyMessageCount?

> `optional` **notifyMessageCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:14007](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14007)

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`notifyMessageCount`](../interfaces/IWebNotificationsInfo.md#notifymessagecount)

***

### notifyMessages

> **notifyMessages**: [`IWebMessageInfo`](../interfaces/IWebMessageInfo.md)[]

Defined in: [WAProto/index.d.ts:14008](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14008)

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`notifyMessages`](../interfaces/IWebNotificationsInfo.md#notifymessages)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:14005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14005)

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`timestamp`](../interfaces/IWebNotificationsInfo.md#timestamp)

***

### unreadChats?

> `optional` **unreadChats**: `null` \| `number`

Defined in: [WAProto/index.d.ts:14006](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14006)

#### Implementation of

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md).[`unreadChats`](../interfaces/IWebNotificationsInfo.md#unreadchats)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:14014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14014)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:14009](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14009)

#### Parameters

##### properties?

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:14011](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14011)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:14010](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14010)

#### Parameters

##### m

[`IWebNotificationsInfo`](../interfaces/IWebNotificationsInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WebNotificationsInfo`](WebNotificationsInfo.md)

Defined in: [WAProto/index.d.ts:14012](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14012)

#### Parameters

##### d

#### Returns

[`WebNotificationsInfo`](WebNotificationsInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:14015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14015)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:14013](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L14013)

#### Parameters

##### m

[`WebNotificationsInfo`](WebNotificationsInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
