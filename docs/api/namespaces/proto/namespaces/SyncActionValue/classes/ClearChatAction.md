# Class: ClearChatAction

Defined in: [WAProto/index.d.ts:11800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11800)

## Implements

- [`IClearChatAction`](../interfaces/IClearChatAction.md)

## Constructors

### new ClearChatAction()

> **new ClearChatAction**(`p`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:11801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11801)

#### Parameters

##### p?

[`IClearChatAction`](../interfaces/IClearChatAction.md)

#### Returns

[`ClearChatAction`](ClearChatAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:11802](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11802)

#### Implementation of

[`IClearChatAction`](../interfaces/IClearChatAction.md).[`messageRange`](../interfaces/IClearChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11808)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:11803](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11803)

#### Parameters

##### properties?

[`IClearChatAction`](../interfaces/IClearChatAction.md)

#### Returns

[`ClearChatAction`](ClearChatAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:11805](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11805)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ClearChatAction`](ClearChatAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11804](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11804)

#### Parameters

##### m

[`IClearChatAction`](../interfaces/IClearChatAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ClearChatAction`](ClearChatAction.md)

Defined in: [WAProto/index.d.ts:11806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11806)

#### Parameters

##### d

#### Returns

[`ClearChatAction`](ClearChatAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11809)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11807](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11807)

#### Parameters

##### m

[`ClearChatAction`](ClearChatAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
