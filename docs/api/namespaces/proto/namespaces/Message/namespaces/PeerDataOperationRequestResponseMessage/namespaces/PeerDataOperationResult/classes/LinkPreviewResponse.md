# Class: LinkPreviewResponse

Defined in: [WAProto/index.d.ts:8105](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8105)

## Implements

- [`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

## Constructors

### new LinkPreviewResponse()

> **new LinkPreviewResponse**(`p`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:8106](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8106)

#### Parameters

##### p?

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

## Properties

### description?

> `optional` **description**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8109](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8109)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`description`](../interfaces/ILinkPreviewResponse.md#description)

***

### hqThumbnail?

> `optional` **hqThumbnail**: `null` \| [`ILinkPreviewHighQualityThumbnail`](../namespaces/LinkPreviewResponse/interfaces/ILinkPreviewHighQualityThumbnail.md)

Defined in: [WAProto/index.d.ts:8113](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8113)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`hqThumbnail`](../interfaces/ILinkPreviewResponse.md#hqthumbnail)

***

### matchText?

> `optional` **matchText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8111](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8111)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`matchText`](../interfaces/ILinkPreviewResponse.md#matchtext)

***

### previewMetadata?

> `optional` **previewMetadata**: `null` \| [`IPaymentLinkPreviewMetadata`](../namespaces/LinkPreviewResponse/interfaces/IPaymentLinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:8114](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8114)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`previewMetadata`](../interfaces/ILinkPreviewResponse.md#previewmetadata)

***

### previewType?

> `optional` **previewType**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8112](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8112)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`previewType`](../interfaces/ILinkPreviewResponse.md#previewtype)

***

### thumbData?

> `optional` **thumbData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8110](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8110)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`thumbData`](../interfaces/ILinkPreviewResponse.md#thumbdata)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8108](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8108)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`title`](../interfaces/ILinkPreviewResponse.md#title)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8107)

#### Implementation of

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md).[`url`](../interfaces/ILinkPreviewResponse.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8120)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:8115](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8115)

#### Parameters

##### properties?

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:8117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8117)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8116)

#### Parameters

##### m

[`ILinkPreviewResponse`](../interfaces/ILinkPreviewResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LinkPreviewResponse`](LinkPreviewResponse.md)

Defined in: [WAProto/index.d.ts:8118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8118)

#### Parameters

##### d

#### Returns

[`LinkPreviewResponse`](LinkPreviewResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8121)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8119)

#### Parameters

##### m

[`LinkPreviewResponse`](LinkPreviewResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
