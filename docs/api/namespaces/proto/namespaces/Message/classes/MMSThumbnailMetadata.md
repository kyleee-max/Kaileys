# Class: MMSThumbnailMetadata

Defined in: [WAProto/index.d.ts:7414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7414)

## Implements

- [`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md)

## Constructors

### new MMSThumbnailMetadata()

> **new MMSThumbnailMetadata**(`p`?): [`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

Defined in: [WAProto/index.d.ts:7415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7415)

#### Parameters

##### p?

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md)

#### Returns

[`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

## Properties

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7419)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`mediaKey`](../interfaces/IMMSThumbnailMetadata.md#mediakey)

***

### mediaKeyDomain?

> `optional` **mediaKeyDomain**: `null` \| [`MediaKeyDomain`](../enumerations/MediaKeyDomain.md)

Defined in: [WAProto/index.d.ts:7423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7423)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`mediaKeyDomain`](../interfaces/IMMSThumbnailMetadata.md#mediakeydomain)

***

### mediaKeyTimestamp?

> `optional` **mediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7420)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`mediaKeyTimestamp`](../interfaces/IMMSThumbnailMetadata.md#mediakeytimestamp)

***

### thumbnailDirectPath?

> `optional` **thumbnailDirectPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7416)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`thumbnailDirectPath`](../interfaces/IMMSThumbnailMetadata.md#thumbnaildirectpath)

***

### thumbnailEncSha256?

> `optional` **thumbnailEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7418)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`thumbnailEncSha256`](../interfaces/IMMSThumbnailMetadata.md#thumbnailencsha256)

***

### thumbnailHeight?

> `optional` **thumbnailHeight**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7421)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`thumbnailHeight`](../interfaces/IMMSThumbnailMetadata.md#thumbnailheight)

***

### thumbnailSha256?

> `optional` **thumbnailSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7417)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`thumbnailSha256`](../interfaces/IMMSThumbnailMetadata.md#thumbnailsha256)

***

### thumbnailWidth?

> `optional` **thumbnailWidth**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7422)

#### Implementation of

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md).[`thumbnailWidth`](../interfaces/IMMSThumbnailMetadata.md#thumbnailwidth)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7429](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7429)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

Defined in: [WAProto/index.d.ts:7424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7424)

#### Parameters

##### properties?

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md)

#### Returns

[`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

Defined in: [WAProto/index.d.ts:7426](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7426)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7425](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7425)

#### Parameters

##### m

[`IMMSThumbnailMetadata`](../interfaces/IMMSThumbnailMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

Defined in: [WAProto/index.d.ts:7427](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7427)

#### Parameters

##### d

#### Returns

[`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7430](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7430)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7428](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7428)

#### Parameters

##### m

[`MMSThumbnailMetadata`](MMSThumbnailMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
