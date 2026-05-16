# Class: LockChatAction

Defined in: [WAProto/index.d.ts:12188](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12188)

## Implements

- [`ILockChatAction`](../interfaces/ILockChatAction.md)

## Constructors

### new LockChatAction()

> **new LockChatAction**(`p`?): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:12189](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12189)

#### Parameters

##### p?

[`ILockChatAction`](../interfaces/ILockChatAction.md)

#### Returns

[`LockChatAction`](LockChatAction.md)

## Properties

### locked?

> `optional` **locked**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12190](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12190)

#### Implementation of

[`ILockChatAction`](../interfaces/ILockChatAction.md).[`locked`](../interfaces/ILockChatAction.md#locked)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12196)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:12191](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12191)

#### Parameters

##### properties?

[`ILockChatAction`](../interfaces/ILockChatAction.md)

#### Returns

[`LockChatAction`](LockChatAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:12193](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12193)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LockChatAction`](LockChatAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12192](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12192)

#### Parameters

##### m

[`ILockChatAction`](../interfaces/ILockChatAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LockChatAction`](LockChatAction.md)

Defined in: [WAProto/index.d.ts:12194](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12194)

#### Parameters

##### d

#### Returns

[`LockChatAction`](LockChatAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12197)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12195)

#### Parameters

##### m

[`LockChatAction`](LockChatAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
