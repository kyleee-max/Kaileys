# Class: ChatAssignmentAction

Defined in: [WAProto/index.d.ts:11768](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11768)

## Implements

- [`IChatAssignmentAction`](../interfaces/IChatAssignmentAction.md)

## Constructors

### new ChatAssignmentAction()

> **new ChatAssignmentAction**(`p`?): [`ChatAssignmentAction`](ChatAssignmentAction.md)

Defined in: [WAProto/index.d.ts:11769](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11769)

#### Parameters

##### p?

[`IChatAssignmentAction`](../interfaces/IChatAssignmentAction.md)

#### Returns

[`ChatAssignmentAction`](ChatAssignmentAction.md)

## Properties

### deviceAgentID?

> `optional` **deviceAgentID**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11770](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11770)

#### Implementation of

[`IChatAssignmentAction`](../interfaces/IChatAssignmentAction.md).[`deviceAgentID`](../interfaces/IChatAssignmentAction.md#deviceagentid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11776)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ChatAssignmentAction`](ChatAssignmentAction.md)

Defined in: [WAProto/index.d.ts:11771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11771)

#### Parameters

##### properties?

[`IChatAssignmentAction`](../interfaces/IChatAssignmentAction.md)

#### Returns

[`ChatAssignmentAction`](ChatAssignmentAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ChatAssignmentAction`](ChatAssignmentAction.md)

Defined in: [WAProto/index.d.ts:11773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11773)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ChatAssignmentAction`](ChatAssignmentAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11772)

#### Parameters

##### m

[`IChatAssignmentAction`](../interfaces/IChatAssignmentAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ChatAssignmentAction`](ChatAssignmentAction.md)

Defined in: [WAProto/index.d.ts:11774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11774)

#### Parameters

##### d

#### Returns

[`ChatAssignmentAction`](ChatAssignmentAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11777](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11777)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11775)

#### Parameters

##### m

[`ChatAssignmentAction`](ChatAssignmentAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
