# Class: VideoEndCard

Defined in: [WAProto/index.d.ts:9301](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9301)

## Implements

- [`IVideoEndCard`](../interfaces/IVideoEndCard.md)

## Constructors

### new VideoEndCard()

> **new VideoEndCard**(`p`?): [`VideoEndCard`](VideoEndCard.md)

Defined in: [WAProto/index.d.ts:9302](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9302)

#### Parameters

##### p?

[`IVideoEndCard`](../interfaces/IVideoEndCard.md)

#### Returns

[`VideoEndCard`](VideoEndCard.md)

## Properties

### caption

> **caption**: `string`

Defined in: [WAProto/index.d.ts:9304](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9304)

#### Implementation of

[`IVideoEndCard`](../interfaces/IVideoEndCard.md).[`caption`](../interfaces/IVideoEndCard.md#caption)

***

### profilePictureUrl

> **profilePictureUrl**: `string`

Defined in: [WAProto/index.d.ts:9306](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9306)

#### Implementation of

[`IVideoEndCard`](../interfaces/IVideoEndCard.md).[`profilePictureUrl`](../interfaces/IVideoEndCard.md#profilepictureurl)

***

### thumbnailImageUrl

> **thumbnailImageUrl**: `string`

Defined in: [WAProto/index.d.ts:9305](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9305)

#### Implementation of

[`IVideoEndCard`](../interfaces/IVideoEndCard.md).[`thumbnailImageUrl`](../interfaces/IVideoEndCard.md#thumbnailimageurl)

***

### username

> **username**: `string`

Defined in: [WAProto/index.d.ts:9303](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9303)

#### Implementation of

[`IVideoEndCard`](../interfaces/IVideoEndCard.md).[`username`](../interfaces/IVideoEndCard.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9312](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9312)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`VideoEndCard`](VideoEndCard.md)

Defined in: [WAProto/index.d.ts:9307](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9307)

#### Parameters

##### properties?

[`IVideoEndCard`](../interfaces/IVideoEndCard.md)

#### Returns

[`VideoEndCard`](VideoEndCard.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`VideoEndCard`](VideoEndCard.md)

Defined in: [WAProto/index.d.ts:9309](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9309)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`VideoEndCard`](VideoEndCard.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9308](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9308)

#### Parameters

##### m

[`IVideoEndCard`](../interfaces/IVideoEndCard.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`VideoEndCard`](VideoEndCard.md)

Defined in: [WAProto/index.d.ts:9310](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9310)

#### Parameters

##### d

#### Returns

[`VideoEndCard`](VideoEndCard.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9313](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9313)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9311](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9311)

#### Parameters

##### m

[`VideoEndCard`](VideoEndCard.md)

##### o?

`IConversionOptions`

#### Returns

`object`
