# Class: ListResponseMessage

Defined in: [WAProto/index.d.ts:7291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7291)

## Implements

- [`IListResponseMessage`](../interfaces/IListResponseMessage.md)

## Constructors

### new ListResponseMessage()

> **new ListResponseMessage**(`p`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:7292](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7292)

#### Parameters

##### p?

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7296](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7296)

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`contextInfo`](../interfaces/IListResponseMessage.md#contextinfo)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7297](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7297)

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`description`](../interfaces/IListResponseMessage.md#description)

***

### listType?

> `optional` **listType**: `null` \| [`ListType`](../namespaces/ListResponseMessage/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:7294](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7294)

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`listType`](../interfaces/IListResponseMessage.md#listtype)

***

### singleSelectReply?

> `optional` **singleSelectReply**: `null` \| [`ISingleSelectReply`](../namespaces/ListResponseMessage/interfaces/ISingleSelectReply.md)

Defined in: [WAProto/index.d.ts:7295](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7295)

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`singleSelectReply`](../interfaces/IListResponseMessage.md#singleselectreply)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7293](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7293)

#### Implementation of

[`IListResponseMessage`](../interfaces/IListResponseMessage.md).[`title`](../interfaces/IListResponseMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7303](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7303)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:7298](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7298)

#### Parameters

##### properties?

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:7300](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7300)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7299](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7299)

#### Parameters

##### m

[`IListResponseMessage`](../interfaces/IListResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ListResponseMessage`](ListResponseMessage.md)

Defined in: [WAProto/index.d.ts:7301](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7301)

#### Parameters

##### d

#### Returns

[`ListResponseMessage`](ListResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7304](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7304)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7302](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7302)

#### Parameters

##### m

[`ListResponseMessage`](ListResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
