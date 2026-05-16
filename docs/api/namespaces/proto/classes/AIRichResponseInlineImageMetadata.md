# Class: AIRichResponseInlineImageMetadata

Defined in: [WAProto/index.d.ts:408](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L408)

## Implements

- [`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md)

## Constructors

### new AIRichResponseInlineImageMetadata()

> **new AIRichResponseInlineImageMetadata**(`p`?): [`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

Defined in: [WAProto/index.d.ts:409](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L409)

#### Parameters

##### p?

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md)

#### Returns

[`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

## Properties

### alignment?

> `optional` **alignment**: `null` \| [`AIRichResponseImageAlignment`](../namespaces/AIRichResponseInlineImageMetadata/enumerations/AIRichResponseImageAlignment.md)

Defined in: [WAProto/index.d.ts:412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L412)

#### Implementation of

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md).[`alignment`](../interfaces/IAIRichResponseInlineImageMetadata.md#alignment)

***

### imageText?

> `optional` **imageText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:411](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L411)

#### Implementation of

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md).[`imageText`](../interfaces/IAIRichResponseInlineImageMetadata.md#imagetext)

***

### imageUrl?

> `optional` **imageUrl**: `null` \| [`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:410](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L410)

#### Implementation of

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md).[`imageUrl`](../interfaces/IAIRichResponseInlineImageMetadata.md#imageurl)

***

### tapLinkUrl?

> `optional` **tapLinkUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L413)

#### Implementation of

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md).[`tapLinkUrl`](../interfaces/IAIRichResponseInlineImageMetadata.md#taplinkurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L419)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

Defined in: [WAProto/index.d.ts:414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L414)

#### Parameters

##### properties?

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md)

#### Returns

[`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

Defined in: [WAProto/index.d.ts:416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L416)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L415)

#### Parameters

##### m

[`IAIRichResponseInlineImageMetadata`](../interfaces/IAIRichResponseInlineImageMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

Defined in: [WAProto/index.d.ts:417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L417)

#### Parameters

##### d

#### Returns

[`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L420)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L418)

#### Parameters

##### m

[`AIRichResponseInlineImageMetadata`](AIRichResponseInlineImageMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
