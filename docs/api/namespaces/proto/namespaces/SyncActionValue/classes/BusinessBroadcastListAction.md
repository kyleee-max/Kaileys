# Class: BusinessBroadcastListAction

Defined in: [WAProto/index.d.ts:11734](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11734)

## Implements

- [`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md)

## Constructors

### new BusinessBroadcastListAction()

> **new BusinessBroadcastListAction**(`p`?): [`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

Defined in: [WAProto/index.d.ts:11735](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11735)

#### Parameters

##### p?

[`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md)

#### Returns

[`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

## Properties

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11736](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11736)

#### Implementation of

[`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md).[`deleted`](../interfaces/IBusinessBroadcastListAction.md#deleted)

***

### listName?

> `optional` **listName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11738](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11738)

#### Implementation of

[`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md).[`listName`](../interfaces/IBusinessBroadcastListAction.md#listname)

***

### participants

> **participants**: [`IBroadcastListParticipant`](../interfaces/IBroadcastListParticipant.md)[]

Defined in: [WAProto/index.d.ts:11737](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11737)

#### Implementation of

[`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md).[`participants`](../interfaces/IBusinessBroadcastListAction.md#participants)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11744)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

Defined in: [WAProto/index.d.ts:11739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11739)

#### Parameters

##### properties?

[`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md)

#### Returns

[`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

Defined in: [WAProto/index.d.ts:11741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11741)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11740)

#### Parameters

##### m

[`IBusinessBroadcastListAction`](../interfaces/IBusinessBroadcastListAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

Defined in: [WAProto/index.d.ts:11742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11742)

#### Parameters

##### d

#### Returns

[`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11745)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11743)

#### Parameters

##### m

[`BusinessBroadcastListAction`](BusinessBroadcastListAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
