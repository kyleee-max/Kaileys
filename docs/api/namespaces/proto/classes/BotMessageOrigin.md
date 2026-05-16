# Class: BotMessageOrigin

Defined in: [WAProto/index.d.ts:1443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1443)

## Implements

- [`IBotMessageOrigin`](../interfaces/IBotMessageOrigin.md)

## Constructors

### new BotMessageOrigin()

> **new BotMessageOrigin**(`p`?): [`BotMessageOrigin`](BotMessageOrigin.md)

Defined in: [WAProto/index.d.ts:1444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1444)

#### Parameters

##### p?

[`IBotMessageOrigin`](../interfaces/IBotMessageOrigin.md)

#### Returns

[`BotMessageOrigin`](BotMessageOrigin.md)

## Properties

### type?

> `optional` **type**: `null` \| [`BOT_MESSAGE_ORIGIN_TYPE_AI_INITIATED`](../namespaces/BotMessageOrigin/enumerations/BotMessageOriginType.md#bot_message_origin_type_ai_initiated)

Defined in: [WAProto/index.d.ts:1445](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1445)

#### Implementation of

[`IBotMessageOrigin`](../interfaces/IBotMessageOrigin.md).[`type`](../interfaces/IBotMessageOrigin.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1451](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1451)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMessageOrigin`](BotMessageOrigin.md)

Defined in: [WAProto/index.d.ts:1446](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1446)

#### Parameters

##### properties?

[`IBotMessageOrigin`](../interfaces/IBotMessageOrigin.md)

#### Returns

[`BotMessageOrigin`](BotMessageOrigin.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMessageOrigin`](BotMessageOrigin.md)

Defined in: [WAProto/index.d.ts:1448](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1448)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMessageOrigin`](BotMessageOrigin.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1447](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1447)

#### Parameters

##### m

[`IBotMessageOrigin`](../interfaces/IBotMessageOrigin.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMessageOrigin`](BotMessageOrigin.md)

Defined in: [WAProto/index.d.ts:1449](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1449)

#### Parameters

##### d

#### Returns

[`BotMessageOrigin`](BotMessageOrigin.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1452](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1452)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1450](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1450)

#### Parameters

##### m

[`BotMessageOrigin`](BotMessageOrigin.md)

##### o?

`IConversionOptions`

#### Returns

`object`
