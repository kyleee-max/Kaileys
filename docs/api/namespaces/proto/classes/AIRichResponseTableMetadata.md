# Class: AIRichResponseTableMetadata

Defined in: [WAProto/index.d.ts:617](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L617)

## Implements

- [`IAIRichResponseTableMetadata`](../interfaces/IAIRichResponseTableMetadata.md)

## Constructors

### new AIRichResponseTableMetadata()

> **new AIRichResponseTableMetadata**(`p`?): [`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

Defined in: [WAProto/index.d.ts:618](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L618)

#### Parameters

##### p?

[`IAIRichResponseTableMetadata`](../interfaces/IAIRichResponseTableMetadata.md)

#### Returns

[`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

## Properties

### rows

> **rows**: [`IAIRichResponseTableRow`](../namespaces/AIRichResponseTableMetadata/interfaces/IAIRichResponseTableRow.md)[]

Defined in: [WAProto/index.d.ts:619](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L619)

#### Implementation of

[`IAIRichResponseTableMetadata`](../interfaces/IAIRichResponseTableMetadata.md).[`rows`](../interfaces/IAIRichResponseTableMetadata.md#rows)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:620](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L620)

#### Implementation of

[`IAIRichResponseTableMetadata`](../interfaces/IAIRichResponseTableMetadata.md).[`title`](../interfaces/IAIRichResponseTableMetadata.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:626](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L626)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

Defined in: [WAProto/index.d.ts:621](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L621)

#### Parameters

##### properties?

[`IAIRichResponseTableMetadata`](../interfaces/IAIRichResponseTableMetadata.md)

#### Returns

[`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

Defined in: [WAProto/index.d.ts:623](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L623)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:622](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L622)

#### Parameters

##### m

[`IAIRichResponseTableMetadata`](../interfaces/IAIRichResponseTableMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

Defined in: [WAProto/index.d.ts:624](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L624)

#### Parameters

##### d

#### Returns

[`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:627](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L627)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:625](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L625)

#### Parameters

##### m

[`AIRichResponseTableMetadata`](AIRichResponseTableMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
