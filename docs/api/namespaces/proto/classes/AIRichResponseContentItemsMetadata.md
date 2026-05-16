# Class: AIRichResponseContentItemsMetadata

Defined in: [WAProto/index.d.ts:272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L272)

## Implements

- [`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

## Constructors

### new AIRichResponseContentItemsMetadata()

> **new AIRichResponseContentItemsMetadata**(`p`?): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:273](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L273)

#### Parameters

##### p?

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

## Properties

### contentType?

> `optional` **contentType**: `null` \| [`ContentType`](../namespaces/AIRichResponseContentItemsMetadata/enumerations/ContentType.md)

Defined in: [WAProto/index.d.ts:275](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L275)

#### Implementation of

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md).[`contentType`](../interfaces/IAIRichResponseContentItemsMetadata.md#contenttype)

***

### itemsMetadata

> **itemsMetadata**: [`IAIRichResponseContentItemMetadata`](../namespaces/AIRichResponseContentItemsMetadata/interfaces/IAIRichResponseContentItemMetadata.md)[]

Defined in: [WAProto/index.d.ts:274](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L274)

#### Implementation of

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md).[`itemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md#itemsmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:281](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L281)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:276](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L276)

#### Parameters

##### properties?

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:278](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L278)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:277](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L277)

#### Parameters

##### m

[`IAIRichResponseContentItemsMetadata`](../interfaces/IAIRichResponseContentItemsMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

Defined in: [WAProto/index.d.ts:279](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L279)

#### Parameters

##### d

#### Returns

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:282](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L282)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:280](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L280)

#### Parameters

##### m

[`AIRichResponseContentItemsMetadata`](AIRichResponseContentItemsMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
