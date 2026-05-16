# Class: DeleteChatAction

Defined in: [WAProto/index.d.ts:11914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11914)

## Implements

- [`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

## Constructors

### new DeleteChatAction()

> **new DeleteChatAction**(`p`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:11915](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11915)

#### Parameters

##### p?

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

## Properties

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:11916](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11916)

#### Implementation of

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md).[`messageRange`](../interfaces/IDeleteChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11922](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11922)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:11917](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11917)

#### Parameters

##### properties?

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:11919](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11919)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11918](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11918)

#### Parameters

##### m

[`IDeleteChatAction`](../interfaces/IDeleteChatAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeleteChatAction`](DeleteChatAction.md)

Defined in: [WAProto/index.d.ts:11920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11920)

#### Parameters

##### d

#### Returns

[`DeleteChatAction`](DeleteChatAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11923)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11921)

#### Parameters

##### m

[`DeleteChatAction`](DeleteChatAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
