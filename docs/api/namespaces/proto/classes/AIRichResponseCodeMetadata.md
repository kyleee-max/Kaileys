# Class: AIRichResponseCodeMetadata

Defined in: [WAProto/index.d.ts:224](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L224)

## Implements

- [`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

## Constructors

### new AIRichResponseCodeMetadata()

> **new AIRichResponseCodeMetadata**(`p`?): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:225](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L225)

#### Parameters

##### p?

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

## Properties

### codeBlocks

> **codeBlocks**: [`IAIRichResponseCodeBlock`](../namespaces/AIRichResponseCodeMetadata/interfaces/IAIRichResponseCodeBlock.md)[]

Defined in: [WAProto/index.d.ts:227](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L227)

#### Implementation of

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md).[`codeBlocks`](../interfaces/IAIRichResponseCodeMetadata.md#codeblocks)

***

### codeLanguage?

> `optional` **codeLanguage**: `null` \| `string`

Defined in: [WAProto/index.d.ts:226](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L226)

#### Implementation of

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md).[`codeLanguage`](../interfaces/IAIRichResponseCodeMetadata.md#codelanguage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L233)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L228)

#### Parameters

##### properties?

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L230)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:229](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L229)

#### Parameters

##### m

[`IAIRichResponseCodeMetadata`](../interfaces/IAIRichResponseCodeMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

Defined in: [WAProto/index.d.ts:231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L231)

#### Parameters

##### d

#### Returns

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L234)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L232)

#### Parameters

##### m

[`AIRichResponseCodeMetadata`](AIRichResponseCodeMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
