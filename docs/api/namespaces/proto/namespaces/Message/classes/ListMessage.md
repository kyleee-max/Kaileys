# Class: ListMessage

Defined in: [WAProto/index.d.ts:7145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7145)

## Implements

- [`IListMessage`](../interfaces/IListMessage.md)

## Constructors

### new ListMessage()

> **new ListMessage**(`p`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:7146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7146)

#### Parameters

##### p?

[`IListMessage`](../interfaces/IListMessage.md)

#### Returns

[`ListMessage`](ListMessage.md)

## Properties

### buttonText?

> `optional` **buttonText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7149](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7149)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`buttonText`](../interfaces/IListMessage.md#buttontext)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7154](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7154)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`contextInfo`](../interfaces/IListMessage.md#contextinfo)

***

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7148)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`description`](../interfaces/IListMessage.md#description)

***

### footerText?

> `optional` **footerText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7153](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7153)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`footerText`](../interfaces/IListMessage.md#footertext)

***

### listType?

> `optional` **listType**: `null` \| [`ListType`](../namespaces/ListMessage/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:7150](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7150)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`listType`](../interfaces/IListMessage.md#listtype)

***

### productListInfo?

> `optional` **productListInfo**: `null` \| [`IProductListInfo`](../namespaces/ListMessage/interfaces/IProductListInfo.md)

Defined in: [WAProto/index.d.ts:7152](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7152)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`productListInfo`](../interfaces/IListMessage.md#productlistinfo)

***

### sections

> **sections**: [`ISection`](../namespaces/ListMessage/interfaces/ISection.md)[]

Defined in: [WAProto/index.d.ts:7151](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7151)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`sections`](../interfaces/IListMessage.md#sections)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7147)

#### Implementation of

[`IListMessage`](../interfaces/IListMessage.md).[`title`](../interfaces/IListMessage.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7160](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7160)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:7155](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7155)

#### Parameters

##### properties?

[`IListMessage`](../interfaces/IListMessage.md)

#### Returns

[`ListMessage`](ListMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:7157](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7157)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ListMessage`](ListMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7156](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7156)

#### Parameters

##### m

[`IListMessage`](../interfaces/IListMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ListMessage`](ListMessage.md)

Defined in: [WAProto/index.d.ts:7158](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7158)

#### Parameters

##### d

#### Returns

[`ListMessage`](ListMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7161](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7161)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7159)

#### Parameters

##### m

[`ListMessage`](ListMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
