# Class: AIRichResponseMapAnnotation

Defined in: [WAProto/index.d.ts:521](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L521)

## Implements

- [`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md)

## Constructors

### new AIRichResponseMapAnnotation()

> **new AIRichResponseMapAnnotation**(`p`?): [`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

Defined in: [WAProto/index.d.ts:522](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L522)

#### Parameters

##### p?

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md)

#### Returns

[`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

## Properties

### annotationNumber?

> `optional` **annotationNumber**: `null` \| `number`

Defined in: [WAProto/index.d.ts:523](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L523)

#### Implementation of

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md).[`annotationNumber`](../interfaces/IAIRichResponseMapAnnotation.md#annotationnumber)

***

### body?

> `optional` **body**: `null` \| `string`

Defined in: [WAProto/index.d.ts:527](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L527)

#### Implementation of

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md).[`body`](../interfaces/IAIRichResponseMapAnnotation.md#body)

***

### latitude?

> `optional` **latitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:524](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L524)

#### Implementation of

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md).[`latitude`](../interfaces/IAIRichResponseMapAnnotation.md#latitude)

***

### longitude?

> `optional` **longitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:525](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L525)

#### Implementation of

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md).[`longitude`](../interfaces/IAIRichResponseMapAnnotation.md#longitude)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:526](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L526)

#### Implementation of

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md).[`title`](../interfaces/IAIRichResponseMapAnnotation.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:533](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L533)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

Defined in: [WAProto/index.d.ts:528](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L528)

#### Parameters

##### properties?

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md)

#### Returns

[`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

Defined in: [WAProto/index.d.ts:530](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L530)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:529](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L529)

#### Parameters

##### m

[`IAIRichResponseMapAnnotation`](../interfaces/IAIRichResponseMapAnnotation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

Defined in: [WAProto/index.d.ts:531](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L531)

#### Parameters

##### d

#### Returns

[`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:534](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L534)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:532](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L532)

#### Parameters

##### m

[`AIRichResponseMapAnnotation`](AIRichResponseMapAnnotation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
