# Class: ThreadID

Defined in: [WAProto/index.d.ts:13257](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13257)

## Implements

- [`IThreadID`](../interfaces/IThreadID.md)

## Constructors

### new ThreadID()

> **new ThreadID**(`p`?): [`ThreadID`](ThreadID.md)

Defined in: [WAProto/index.d.ts:13258](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13258)

#### Parameters

##### p?

[`IThreadID`](../interfaces/IThreadID.md)

#### Returns

[`ThreadID`](ThreadID.md)

## Properties

### threadKey?

> `optional` **threadKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:13260](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13260)

#### Implementation of

[`IThreadID`](../interfaces/IThreadID.md).[`threadKey`](../interfaces/IThreadID.md#threadkey)

***

### threadType?

> `optional` **threadType**: `null` \| [`ThreadType`](../namespaces/ThreadID/enumerations/ThreadType.md)

Defined in: [WAProto/index.d.ts:13259](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13259)

#### Implementation of

[`IThreadID`](../interfaces/IThreadID.md).[`threadType`](../interfaces/IThreadID.md#threadtype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13266](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13266)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ThreadID`](ThreadID.md)

Defined in: [WAProto/index.d.ts:13261](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13261)

#### Parameters

##### properties?

[`IThreadID`](../interfaces/IThreadID.md)

#### Returns

[`ThreadID`](ThreadID.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ThreadID`](ThreadID.md)

Defined in: [WAProto/index.d.ts:13263](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13263)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ThreadID`](ThreadID.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13262](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13262)

#### Parameters

##### m

[`IThreadID`](../interfaces/IThreadID.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ThreadID`](ThreadID.md)

Defined in: [WAProto/index.d.ts:13264](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13264)

#### Parameters

##### d

#### Returns

[`ThreadID`](ThreadID.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13267](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13267)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13265](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13265)

#### Parameters

##### m

[`ThreadID`](ThreadID.md)

##### o?

`IConversionOptions`

#### Returns

`object`
