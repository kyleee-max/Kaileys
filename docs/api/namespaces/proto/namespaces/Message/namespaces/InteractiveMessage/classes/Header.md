# Class: Header

Defined in: [WAProto/index.d.ts:6865](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6865)

## Implements

- [`IHeader`](../interfaces/IHeader.md)

## Constructors

### new Header()

> **new Header**(`p`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:6866](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6866)

#### Parameters

##### p?

[`IHeader`](../interfaces/IHeader.md)

#### Returns

[`Header`](Header.md)

## Properties

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../../../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:6870](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6870)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`documentMessage`](../interfaces/IHeader.md#documentmessage)

***

### hasMediaAttachment?

> `optional` **hasMediaAttachment**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6869](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6869)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`hasMediaAttachment`](../interfaces/IHeader.md#hasmediaattachment)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:6871](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6871)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`imageMessage`](../interfaces/IHeader.md#imagemessage)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6872](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6872)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`jpegThumbnail`](../interfaces/IHeader.md#jpegthumbnail)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../../../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:6874](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6874)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`locationMessage`](../interfaces/IHeader.md#locationmessage)

***

### media?

> `optional` **media**: `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"` \| `"productMessage"` \| `"jpegThumbnail"`

Defined in: [WAProto/index.d.ts:6876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6876)

***

### productMessage?

> `optional` **productMessage**: `null` \| [`IProductMessage`](../../../interfaces/IProductMessage.md)

Defined in: [WAProto/index.d.ts:6875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6875)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`productMessage`](../interfaces/IHeader.md#productmessage)

***

### subtitle?

> `optional` **subtitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6868](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6868)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`subtitle`](../interfaces/IHeader.md#subtitle)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6867](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6867)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`title`](../interfaces/IHeader.md#title)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../../../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:6873](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6873)

#### Implementation of

[`IHeader`](../interfaces/IHeader.md).[`videoMessage`](../interfaces/IHeader.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6882)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:6877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6877)

#### Parameters

##### properties?

[`IHeader`](../interfaces/IHeader.md)

#### Returns

[`Header`](Header.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:6879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6879)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Header`](Header.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6878)

#### Parameters

##### m

[`IHeader`](../interfaces/IHeader.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Header`](Header.md)

Defined in: [WAProto/index.d.ts:6880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6880)

#### Parameters

##### d

#### Returns

[`Header`](Header.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6883)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6881)

#### Parameters

##### m

[`Header`](Header.md)

##### o?

`IConversionOptions`

#### Returns

`object`
