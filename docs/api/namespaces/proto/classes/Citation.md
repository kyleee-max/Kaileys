# Class: Citation

Defined in: [WAProto/index.d.ts:2597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2597)

## Implements

- [`ICitation`](../interfaces/ICitation.md)

## Constructors

### new Citation()

> **new Citation**(`p`?): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:2598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2598)

#### Parameters

##### p?

[`ICitation`](../interfaces/ICitation.md)

#### Returns

[`Citation`](Citation.md)

## Properties

### cmsId

> **cmsId**: `string`

Defined in: [WAProto/index.d.ts:2601](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2601)

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`cmsId`](../interfaces/ICitation.md#cmsid)

***

### imageUrl

> **imageUrl**: `string`

Defined in: [WAProto/index.d.ts:2602](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2602)

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`imageUrl`](../interfaces/ICitation.md#imageurl)

***

### subtitle

> **subtitle**: `string`

Defined in: [WAProto/index.d.ts:2600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2600)

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`subtitle`](../interfaces/ICitation.md#subtitle)

***

### title

> **title**: `string`

Defined in: [WAProto/index.d.ts:2599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2599)

#### Implementation of

[`ICitation`](../interfaces/ICitation.md).[`title`](../interfaces/ICitation.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2608](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2608)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:2603](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2603)

#### Parameters

##### properties?

[`ICitation`](../interfaces/ICitation.md)

#### Returns

[`Citation`](Citation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:2605](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2605)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Citation`](Citation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2604](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2604)

#### Parameters

##### m

[`ICitation`](../interfaces/ICitation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Citation`](Citation.md)

Defined in: [WAProto/index.d.ts:2606](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2606)

#### Parameters

##### d

#### Returns

[`Citation`](Citation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2609](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2609)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2607](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2607)

#### Parameters

##### m

[`Citation`](Citation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
