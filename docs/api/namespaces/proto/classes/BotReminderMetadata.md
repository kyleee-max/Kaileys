# Class: BotReminderMetadata

Defined in: [WAProto/index.d.ts:2015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2015)

## Implements

- [`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

## Constructors

### new BotReminderMetadata()

> **new BotReminderMetadata**(`p`?): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:2016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2016)

#### Parameters

##### p?

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

## Properties

### action?

> `optional` **action**: `null` \| [`ReminderAction`](../namespaces/BotReminderMetadata/enumerations/ReminderAction.md)

Defined in: [WAProto/index.d.ts:2018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2018)

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`action`](../interfaces/IBotReminderMetadata.md#action)

***

### frequency?

> `optional` **frequency**: `null` \| [`ReminderFrequency`](../namespaces/BotReminderMetadata/enumerations/ReminderFrequency.md)

Defined in: [WAProto/index.d.ts:2021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2021)

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`frequency`](../interfaces/IBotReminderMetadata.md#frequency)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2019)

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`name`](../interfaces/IBotReminderMetadata.md#name)

***

### nextTriggerTimestamp?

> `optional` **nextTriggerTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2020)

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`nextTriggerTimestamp`](../interfaces/IBotReminderMetadata.md#nexttriggertimestamp)

***

### requestMessageKey?

> `optional` **requestMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:2017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2017)

#### Implementation of

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md).[`requestMessageKey`](../interfaces/IBotReminderMetadata.md#requestmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2027](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2027)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:2022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2022)

#### Parameters

##### properties?

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:2024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2024)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2023)

#### Parameters

##### m

[`IBotReminderMetadata`](../interfaces/IBotReminderMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotReminderMetadata`](BotReminderMetadata.md)

Defined in: [WAProto/index.d.ts:2025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2025)

#### Parameters

##### d

#### Returns

[`BotReminderMetadata`](BotReminderMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2028](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2028)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2026](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2026)

#### Parameters

##### m

[`BotReminderMetadata`](BotReminderMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
