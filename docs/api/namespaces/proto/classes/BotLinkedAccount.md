# Class: BotLinkedAccount

Defined in: [WAProto/index.d.ts:1309](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1309)

## Implements

- [`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

## Constructors

### new BotLinkedAccount()

> **new BotLinkedAccount**(`p`?): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:1310](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1310)

#### Parameters

##### p?

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

## Properties

### type?

> `optional` **type**: `null` \| [`BOT_LINKED_ACCOUNT_TYPE_1P`](../namespaces/BotLinkedAccount/enumerations/BotLinkedAccountType.md#bot_linked_account_type_1p)

Defined in: [WAProto/index.d.ts:1311](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1311)

#### Implementation of

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md).[`type`](../interfaces/IBotLinkedAccount.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1317](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1317)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:1312](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1312)

#### Parameters

##### properties?

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:1314](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1314)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1313](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1313)

#### Parameters

##### m

[`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotLinkedAccount`](BotLinkedAccount.md)

Defined in: [WAProto/index.d.ts:1315](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1315)

#### Parameters

##### d

#### Returns

[`BotLinkedAccount`](BotLinkedAccount.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1318)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1316](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1316)

#### Parameters

##### m

[`BotLinkedAccount`](BotLinkedAccount.md)

##### o?

`IConversionOptions`

#### Returns

`object`
