# Class: ChatLockSettings

Defined in: [WAProto/index.d.ts:2462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2462)

## Implements

- [`IChatLockSettings`](../interfaces/IChatLockSettings.md)

## Constructors

### new ChatLockSettings()

> **new ChatLockSettings**(`p`?): [`ChatLockSettings`](ChatLockSettings.md)

Defined in: [WAProto/index.d.ts:2463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2463)

#### Parameters

##### p?

[`IChatLockSettings`](../interfaces/IChatLockSettings.md)

#### Returns

[`ChatLockSettings`](ChatLockSettings.md)

## Properties

### hideLockedChats?

> `optional` **hideLockedChats**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2464)

#### Implementation of

[`IChatLockSettings`](../interfaces/IChatLockSettings.md).[`hideLockedChats`](../interfaces/IChatLockSettings.md#hidelockedchats)

***

### secretCode?

> `optional` **secretCode**: `null` \| [`IUserPassword`](../interfaces/IUserPassword.md)

Defined in: [WAProto/index.d.ts:2465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2465)

#### Implementation of

[`IChatLockSettings`](../interfaces/IChatLockSettings.md).[`secretCode`](../interfaces/IChatLockSettings.md#secretcode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2471](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2471)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ChatLockSettings`](ChatLockSettings.md)

Defined in: [WAProto/index.d.ts:2466](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2466)

#### Parameters

##### properties?

[`IChatLockSettings`](../interfaces/IChatLockSettings.md)

#### Returns

[`ChatLockSettings`](ChatLockSettings.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ChatLockSettings`](ChatLockSettings.md)

Defined in: [WAProto/index.d.ts:2468](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2468)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ChatLockSettings`](ChatLockSettings.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2467](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2467)

#### Parameters

##### m

[`IChatLockSettings`](../interfaces/IChatLockSettings.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ChatLockSettings`](ChatLockSettings.md)

Defined in: [WAProto/index.d.ts:2469](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2469)

#### Parameters

##### d

#### Returns

[`ChatLockSettings`](ChatLockSettings.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2472](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2472)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2470](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2470)

#### Parameters

##### m

[`ChatLockSettings`](ChatLockSettings.md)

##### o?

`IConversionOptions`

#### Returns

`object`
