# Class: UsernameChatStartModeAction

Defined in: [WAProto/index.d.ts:12928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12928)

## Implements

- [`IUsernameChatStartModeAction`](../interfaces/IUsernameChatStartModeAction.md)

## Constructors

### new UsernameChatStartModeAction()

> **new UsernameChatStartModeAction**(`p`?): [`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

Defined in: [WAProto/index.d.ts:12929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12929)

#### Parameters

##### p?

[`IUsernameChatStartModeAction`](../interfaces/IUsernameChatStartModeAction.md)

#### Returns

[`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

## Properties

### chatStartMode?

> `optional` **chatStartMode**: `null` \| [`ChatStartMode`](../namespaces/UsernameChatStartModeAction/enumerations/ChatStartMode.md)

Defined in: [WAProto/index.d.ts:12930](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12930)

#### Implementation of

[`IUsernameChatStartModeAction`](../interfaces/IUsernameChatStartModeAction.md).[`chatStartMode`](../interfaces/IUsernameChatStartModeAction.md#chatstartmode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12936](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12936)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

Defined in: [WAProto/index.d.ts:12931](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12931)

#### Parameters

##### properties?

[`IUsernameChatStartModeAction`](../interfaces/IUsernameChatStartModeAction.md)

#### Returns

[`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

Defined in: [WAProto/index.d.ts:12933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12933)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12932](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12932)

#### Parameters

##### m

[`IUsernameChatStartModeAction`](../interfaces/IUsernameChatStartModeAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

Defined in: [WAProto/index.d.ts:12934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12934)

#### Parameters

##### d

#### Returns

[`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12937](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12937)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12935)

#### Parameters

##### m

[`UsernameChatStartModeAction`](UsernameChatStartModeAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
