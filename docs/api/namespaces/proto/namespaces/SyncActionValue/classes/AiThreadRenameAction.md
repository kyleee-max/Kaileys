# Class: AiThreadRenameAction

Defined in: [WAProto/index.d.ts:11605](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11605)

## Implements

- [`IAiThreadRenameAction`](../interfaces/IAiThreadRenameAction.md)

## Constructors

### new AiThreadRenameAction()

> **new AiThreadRenameAction**(`p`?): [`AiThreadRenameAction`](AiThreadRenameAction.md)

Defined in: [WAProto/index.d.ts:11606](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11606)

#### Parameters

##### p?

[`IAiThreadRenameAction`](../interfaces/IAiThreadRenameAction.md)

#### Returns

[`AiThreadRenameAction`](AiThreadRenameAction.md)

## Properties

### newTitle?

> `optional` **newTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11607](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11607)

#### Implementation of

[`IAiThreadRenameAction`](../interfaces/IAiThreadRenameAction.md).[`newTitle`](../interfaces/IAiThreadRenameAction.md#newtitle)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11613](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11613)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AiThreadRenameAction`](AiThreadRenameAction.md)

Defined in: [WAProto/index.d.ts:11608](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11608)

#### Parameters

##### properties?

[`IAiThreadRenameAction`](../interfaces/IAiThreadRenameAction.md)

#### Returns

[`AiThreadRenameAction`](AiThreadRenameAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AiThreadRenameAction`](AiThreadRenameAction.md)

Defined in: [WAProto/index.d.ts:11610](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11610)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AiThreadRenameAction`](AiThreadRenameAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11609](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11609)

#### Parameters

##### m

[`IAiThreadRenameAction`](../interfaces/IAiThreadRenameAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AiThreadRenameAction`](AiThreadRenameAction.md)

Defined in: [WAProto/index.d.ts:11611](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11611)

#### Parameters

##### d

#### Returns

[`AiThreadRenameAction`](AiThreadRenameAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11614](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11614)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11612](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11612)

#### Parameters

##### m

[`AiThreadRenameAction`](AiThreadRenameAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
