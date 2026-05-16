# Class: AIRichResponseLatexMetadata

Defined in: [WAProto/index.d.ts:437](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L437)

## Implements

- [`IAIRichResponseLatexMetadata`](../interfaces/IAIRichResponseLatexMetadata.md)

## Constructors

### new AIRichResponseLatexMetadata()

> **new AIRichResponseLatexMetadata**(`p`?): [`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

Defined in: [WAProto/index.d.ts:438](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L438)

#### Parameters

##### p?

[`IAIRichResponseLatexMetadata`](../interfaces/IAIRichResponseLatexMetadata.md)

#### Returns

[`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

## Properties

### expressions

> **expressions**: [`IAIRichResponseLatexExpression`](../namespaces/AIRichResponseLatexMetadata/interfaces/IAIRichResponseLatexExpression.md)[]

Defined in: [WAProto/index.d.ts:440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L440)

#### Implementation of

[`IAIRichResponseLatexMetadata`](../interfaces/IAIRichResponseLatexMetadata.md).[`expressions`](../interfaces/IAIRichResponseLatexMetadata.md#expressions)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L439)

#### Implementation of

[`IAIRichResponseLatexMetadata`](../interfaces/IAIRichResponseLatexMetadata.md).[`text`](../interfaces/IAIRichResponseLatexMetadata.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:446](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L446)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

Defined in: [WAProto/index.d.ts:441](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L441)

#### Parameters

##### properties?

[`IAIRichResponseLatexMetadata`](../interfaces/IAIRichResponseLatexMetadata.md)

#### Returns

[`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

Defined in: [WAProto/index.d.ts:443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L443)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:442](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L442)

#### Parameters

##### m

[`IAIRichResponseLatexMetadata`](../interfaces/IAIRichResponseLatexMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

Defined in: [WAProto/index.d.ts:444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L444)

#### Parameters

##### d

#### Returns

[`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:447](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L447)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:445](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L445)

#### Parameters

##### m

[`AIRichResponseLatexMetadata`](AIRichResponseLatexMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
