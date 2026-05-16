# Class: ChatAssignmentOpenedStatusAction

Defined in: [WAProto/index.d.ts:11784](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11784)

## Implements

- [`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

## Constructors

### new ChatAssignmentOpenedStatusAction()

> **new ChatAssignmentOpenedStatusAction**(`p`?): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:11785](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11785)

#### Parameters

##### p?

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

## Properties

### chatOpened?

> `optional` **chatOpened**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11786](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11786)

#### Implementation of

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md).[`chatOpened`](../interfaces/IChatAssignmentOpenedStatusAction.md#chatopened)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11792)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:11787](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11787)

#### Parameters

##### properties?

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:11789](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11789)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11788](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11788)

#### Parameters

##### m

[`IChatAssignmentOpenedStatusAction`](../interfaces/IChatAssignmentOpenedStatusAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

Defined in: [WAProto/index.d.ts:11790](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11790)

#### Parameters

##### d

#### Returns

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11793)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11791)

#### Parameters

##### m

[`ChatAssignmentOpenedStatusAction`](ChatAssignmentOpenedStatusAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
