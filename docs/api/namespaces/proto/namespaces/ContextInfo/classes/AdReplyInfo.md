# Class: AdReplyInfo

Defined in: [WAProto/index.d.ts:3262](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3262)

## Implements

- [`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

## Constructors

### new AdReplyInfo()

> **new AdReplyInfo**(`p`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:3263](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3263)

#### Parameters

##### p?

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

## Properties

### advertiserName?

> `optional` **advertiserName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3264](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3264)

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`advertiserName`](../interfaces/IAdReplyInfo.md#advertisername)

***

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3267](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3267)

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`caption`](../interfaces/IAdReplyInfo.md#caption)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3266](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3266)

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`jpegThumbnail`](../interfaces/IAdReplyInfo.md#jpegthumbnail)

***

### mediaType?

> `optional` **mediaType**: `null` \| [`MediaType`](../namespaces/AdReplyInfo/enumerations/MediaType.md)

Defined in: [WAProto/index.d.ts:3265](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3265)

#### Implementation of

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md).[`mediaType`](../interfaces/IAdReplyInfo.md#mediatype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3273](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3273)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:3268](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3268)

#### Parameters

##### properties?

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:3270](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3270)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3269](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3269)

#### Parameters

##### m

[`IAdReplyInfo`](../interfaces/IAdReplyInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AdReplyInfo`](AdReplyInfo.md)

Defined in: [WAProto/index.d.ts:3271](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3271)

#### Parameters

##### d

#### Returns

[`AdReplyInfo`](AdReplyInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3274](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3274)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3272)

#### Parameters

##### m

[`AdReplyInfo`](AdReplyInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
