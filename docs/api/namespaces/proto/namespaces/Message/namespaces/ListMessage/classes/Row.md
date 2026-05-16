# Class: Row

Defined in: [WAProto/index.d.ts:7250](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7250)

## Implements

- [`IRow`](../interfaces/IRow.md)

## Constructors

### new Row()

> **new Row**(`p`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:7251](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7251)

#### Parameters

##### p?

[`IRow`](../interfaces/IRow.md)

#### Returns

[`Row`](Row.md)

## Properties

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7253](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7253)

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`description`](../interfaces/IRow.md#description)

***

### rowId?

> `optional` **rowId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7254](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7254)

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`rowId`](../interfaces/IRow.md#rowid)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7252](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7252)

#### Implementation of

[`IRow`](../interfaces/IRow.md).[`title`](../interfaces/IRow.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7260](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7260)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:7255](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7255)

#### Parameters

##### properties?

[`IRow`](../interfaces/IRow.md)

#### Returns

[`Row`](Row.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:7257](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7257)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Row`](Row.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7256](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7256)

#### Parameters

##### m

[`IRow`](../interfaces/IRow.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Row`](Row.md)

Defined in: [WAProto/index.d.ts:7258](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7258)

#### Parameters

##### d

#### Returns

[`Row`](Row.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7261](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7261)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7259](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7259)

#### Parameters

##### m

[`Row`](Row.md)

##### o?

`IConversionOptions`

#### Returns

`object`
