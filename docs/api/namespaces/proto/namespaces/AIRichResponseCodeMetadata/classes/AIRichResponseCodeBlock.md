# Class: AIRichResponseCodeBlock

Defined in: [WAProto/index.d.ts:244](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L244)

## Implements

- [`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

## Constructors

### new AIRichResponseCodeBlock()

> **new AIRichResponseCodeBlock**(`p`?): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:245](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L245)

#### Parameters

##### p?

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

## Properties

### codeContent?

> `optional` **codeContent**: `null` \| `string`

Defined in: [WAProto/index.d.ts:247](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L247)

#### Implementation of

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md).[`codeContent`](../interfaces/IAIRichResponseCodeBlock.md#codecontent)

***

### highlightType?

> `optional` **highlightType**: `null` \| [`AIRichResponseCodeHighlightType`](../enumerations/AIRichResponseCodeHighlightType.md)

Defined in: [WAProto/index.d.ts:246](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L246)

#### Implementation of

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md).[`highlightType`](../interfaces/IAIRichResponseCodeBlock.md#highlighttype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:253](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L253)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:248](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L248)

#### Parameters

##### properties?

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:250](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L250)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:249](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L249)

#### Parameters

##### m

[`IAIRichResponseCodeBlock`](../interfaces/IAIRichResponseCodeBlock.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

Defined in: [WAProto/index.d.ts:251](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L251)

#### Parameters

##### d

#### Returns

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:254](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L254)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:252](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L252)

#### Parameters

##### m

[`AIRichResponseCodeBlock`](AIRichResponseCodeBlock.md)

##### o?

`IConversionOptions`

#### Returns

`object`
