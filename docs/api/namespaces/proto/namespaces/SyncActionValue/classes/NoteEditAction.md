# Class: NoteEditAction

Defined in: [WAProto/index.d.ts:12386](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12386)

## Implements

- [`INoteEditAction`](../interfaces/INoteEditAction.md)

## Constructors

### new NoteEditAction()

> **new NoteEditAction**(`p`?): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:12387](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12387)

#### Parameters

##### p?

[`INoteEditAction`](../interfaces/INoteEditAction.md)

#### Returns

[`NoteEditAction`](NoteEditAction.md)

## Properties

### chatJid?

> `optional` **chatJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12389](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12389)

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`chatJid`](../interfaces/INoteEditAction.md#chatjid)

***

### createdAt?

> `optional` **createdAt**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12390](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12390)

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`createdAt`](../interfaces/INoteEditAction.md#createdat)

***

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12391](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12391)

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`deleted`](../interfaces/INoteEditAction.md#deleted)

***

### type?

> `optional` **type**: `null` \| [`NoteType`](../namespaces/NoteEditAction/enumerations/NoteType.md)

Defined in: [WAProto/index.d.ts:12388](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12388)

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`type`](../interfaces/INoteEditAction.md#type)

***

### unstructuredContent?

> `optional` **unstructuredContent**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12392](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12392)

#### Implementation of

[`INoteEditAction`](../interfaces/INoteEditAction.md).[`unstructuredContent`](../interfaces/INoteEditAction.md#unstructuredcontent)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12398](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12398)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:12393](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12393)

#### Parameters

##### properties?

[`INoteEditAction`](../interfaces/INoteEditAction.md)

#### Returns

[`NoteEditAction`](NoteEditAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:12395](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12395)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NoteEditAction`](NoteEditAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12394](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12394)

#### Parameters

##### m

[`INoteEditAction`](../interfaces/INoteEditAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NoteEditAction`](NoteEditAction.md)

Defined in: [WAProto/index.d.ts:12396](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12396)

#### Parameters

##### d

#### Returns

[`NoteEditAction`](NoteEditAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12399](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12399)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12397](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12397)

#### Parameters

##### m

[`NoteEditAction`](NoteEditAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
