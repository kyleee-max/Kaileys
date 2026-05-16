# Class: PnForLidChatAction

Defined in: [WAProto/index.d.ts:12513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12513)

## Implements

- [`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

## Constructors

### new PnForLidChatAction()

> **new PnForLidChatAction**(`p`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:12514](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12514)

#### Parameters

##### p?

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

## Properties

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12515](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12515)

#### Implementation of

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md).[`pnJid`](../interfaces/IPnForLidChatAction.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12521](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12521)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:12516](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12516)

#### Parameters

##### properties?

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:12518](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12518)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12517](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12517)

#### Parameters

##### m

[`IPnForLidChatAction`](../interfaces/IPnForLidChatAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PnForLidChatAction`](PnForLidChatAction.md)

Defined in: [WAProto/index.d.ts:12519](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12519)

#### Parameters

##### d

#### Returns

[`PnForLidChatAction`](PnForLidChatAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12522](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12522)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12520](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12520)

#### Parameters

##### m

[`PnForLidChatAction`](PnForLidChatAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
