# Class: ArchiveChatAction

Defined in: [WAProto/index.d.ts:11638](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11638)

## Implements

- [`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

## Constructors

### new ArchiveChatAction()

> **new ArchiveChatAction**(`p`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:11639](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11639)

#### Parameters

##### p?

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

## Properties

### archived?

> `optional` **archived**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11640](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11640)

#### Implementation of

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md).[`archived`](../interfaces/IArchiveChatAction.md#archived)

***

### messageRange?

> `optional` **messageRange**: `null` \| [`ISyncActionMessageRange`](../interfaces/ISyncActionMessageRange.md)

Defined in: [WAProto/index.d.ts:11641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11641)

#### Implementation of

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md).[`messageRange`](../interfaces/IArchiveChatAction.md#messagerange)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11647](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11647)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:11642](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11642)

#### Parameters

##### properties?

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:11644](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11644)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11643](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11643)

#### Parameters

##### m

[`IArchiveChatAction`](../interfaces/IArchiveChatAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ArchiveChatAction`](ArchiveChatAction.md)

Defined in: [WAProto/index.d.ts:11645](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11645)

#### Parameters

##### d

#### Returns

[`ArchiveChatAction`](ArchiveChatAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11648](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11648)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11646](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11646)

#### Parameters

##### m

[`ArchiveChatAction`](ArchiveChatAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
