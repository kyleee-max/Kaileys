# Class: UserStatusMuteAction

Defined in: [WAProto/index.d.ts:12912](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12912)

## Implements

- [`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

## Constructors

### new UserStatusMuteAction()

> **new UserStatusMuteAction**(`p`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:12913](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12913)

#### Parameters

##### p?

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

## Properties

### muted?

> `optional` **muted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12914)

#### Implementation of

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md).[`muted`](../interfaces/IUserStatusMuteAction.md#muted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12920)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:12915](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12915)

#### Parameters

##### properties?

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:12917](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12917)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12916](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12916)

#### Parameters

##### m

[`IUserStatusMuteAction`](../interfaces/IUserStatusMuteAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UserStatusMuteAction`](UserStatusMuteAction.md)

Defined in: [WAProto/index.d.ts:12918](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12918)

#### Parameters

##### d

#### Returns

[`UserStatusMuteAction`](UserStatusMuteAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12921)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12919](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12919)

#### Parameters

##### m

[`UserStatusMuteAction`](UserStatusMuteAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
