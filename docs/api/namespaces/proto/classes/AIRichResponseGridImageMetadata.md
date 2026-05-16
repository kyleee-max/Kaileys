# Class: AIRichResponseGridImageMetadata

Defined in: [WAProto/index.d.ts:368](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L368)

## Implements

- [`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

## Constructors

### new AIRichResponseGridImageMetadata()

> **new AIRichResponseGridImageMetadata**(`p`?): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:369](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L369)

#### Parameters

##### p?

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

## Properties

### gridImageUrl?

> `optional` **gridImageUrl**: `null` \| [`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)

Defined in: [WAProto/index.d.ts:370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L370)

#### Implementation of

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md).[`gridImageUrl`](../interfaces/IAIRichResponseGridImageMetadata.md#gridimageurl)

***

### imageUrls

> **imageUrls**: [`IAIRichResponseImageURL`](../interfaces/IAIRichResponseImageURL.md)[]

Defined in: [WAProto/index.d.ts:371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L371)

#### Implementation of

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md).[`imageUrls`](../interfaces/IAIRichResponseGridImageMetadata.md#imageurls)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:377](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L377)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L372)

#### Parameters

##### properties?

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:374](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L374)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L373)

#### Parameters

##### m

[`IAIRichResponseGridImageMetadata`](../interfaces/IAIRichResponseGridImageMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

Defined in: [WAProto/index.d.ts:375](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L375)

#### Parameters

##### d

#### Returns

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:378](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L378)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:376](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L376)

#### Parameters

##### m

[`AIRichResponseGridImageMetadata`](AIRichResponseGridImageMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
