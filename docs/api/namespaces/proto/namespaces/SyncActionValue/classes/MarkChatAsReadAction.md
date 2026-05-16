# Class: MarkChatAsReadAction

Defined in: [WAProto/index.d.ts:12230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12230)

## Implements

- [`IMarkChatAsReadAction`](../interfaces/IMarkChatAsReadAction.md)

## Constructors

### new MarkChatAsReadAction()

> **new MarkChatAsReadAction**(`p`?): [`MarkChatAsReadAction`](MarkChatAsReadAction.md)

Defined in: [WAProto/index.d.ts:12231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12231)

#### Parameters

##### p?

[`IMarkChatAsReadAction`](../interfaces/IMarkChatAsReadAction.md)

#### Returns

[`MarkChatAsReadAction`](MarkChatAsReadAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:12233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12233)

#### Implementation of

[`IMarkChatAsReadAction`](../interfaces/IMarkChatAsReadAction.md).[`messageRange`](../interfaces/IMarkChatAsReadAction.md#messagerange)

***

### read?

> `optional` **read**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12232)

#### Implementation of

[`IMarkChatAsReadAction`](../interfaces/IMarkChatAsReadAction.md).[`read`](../interfaces/IMarkChatAsReadAction.md#read)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12239](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12239)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MarkChatAsReadAction`](MarkChatAsReadAction.md)

Defined in: [WAProto/index.d.ts:12234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12234)

#### Parameters

##### properties?

[`IMarkChatAsReadAction`](../interfaces/IMarkChatAsReadAction.md)

#### Returns

[`MarkChatAsReadAction`](MarkChatAsReadAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MarkChatAsReadAction`](MarkChatAsReadAction.md)

Defined in: [WAProto/index.d.ts:12236](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12236)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MarkChatAsReadAction`](MarkChatAsReadAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12235](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12235)

#### Parameters

##### m

[`IMarkChatAsReadAction`](../interfaces/IMarkChatAsReadAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MarkChatAsReadAction`](MarkChatAsReadAction.md)

Defined in: [WAProto/index.d.ts:12237](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12237)

#### Parameters

##### d

#### Returns

[`MarkChatAsReadAction`](MarkChatAsReadAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12240](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12240)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12238](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12238)

#### Parameters

##### m

[`MarkChatAsReadAction`](MarkChatAsReadAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
