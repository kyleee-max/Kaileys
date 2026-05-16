# Class: BotWelcomeRequestAction

Defined in: [WAProto/index.d.ts:11682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11682)

## Implements

- [`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

## Constructors

### new BotWelcomeRequestAction()

> **new BotWelcomeRequestAction**(`p`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:11683](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11683)

#### Parameters

##### p?

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

## Properties

### isSent?

> `optional` **isSent**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11684](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11684)

#### Implementation of

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md).[`isSent`](../interfaces/IBotWelcomeRequestAction.md#issent)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11690](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11690)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:11685](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11685)

#### Parameters

##### properties?

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:11687](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11687)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11686](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11686)

#### Parameters

##### m

[`IBotWelcomeRequestAction`](../interfaces/IBotWelcomeRequestAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

Defined in: [WAProto/index.d.ts:11688](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11688)

#### Parameters

##### d

#### Returns

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11691](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11691)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11689](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11689)

#### Parameters

##### m

[`BotWelcomeRequestAction`](BotWelcomeRequestAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
