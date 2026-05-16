# Class: InvoiceMessage

Defined in: [WAProto/index.d.ts:7041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7041)

## Implements

- [`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

## Constructors

### new InvoiceMessage()

> **new InvoiceMessage**(`p`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:7042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7042)

#### Parameters

##### p?

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

## Properties

### attachmentDirectPath?

> `optional` **attachmentDirectPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7051](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7051)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentDirectPath`](../interfaces/IInvoiceMessage.md#attachmentdirectpath)

***

### attachmentFileEncSha256?

> `optional` **attachmentFileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7050](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7050)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentFileEncSha256`](../interfaces/IInvoiceMessage.md#attachmentfileencsha256)

***

### attachmentFileSha256?

> `optional` **attachmentFileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7049](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7049)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentFileSha256`](../interfaces/IInvoiceMessage.md#attachmentfilesha256)

***

### attachmentJpegThumbnail?

> `optional` **attachmentJpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7052](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7052)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentJpegThumbnail`](../interfaces/IInvoiceMessage.md#attachmentjpegthumbnail)

***

### attachmentMediaKey?

> `optional` **attachmentMediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7047](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7047)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMediaKey`](../interfaces/IInvoiceMessage.md#attachmentmediakey)

***

### attachmentMediaKeyTimestamp?

> `optional` **attachmentMediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7048](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7048)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMediaKeyTimestamp`](../interfaces/IInvoiceMessage.md#attachmentmediakeytimestamp)

***

### attachmentMimetype?

> `optional` **attachmentMimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7046](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7046)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentMimetype`](../interfaces/IInvoiceMessage.md#attachmentmimetype)

***

### attachmentType?

> `optional` **attachmentType**: `null` \| [`AttachmentType`](../namespaces/InvoiceMessage/enumerations/AttachmentType.md)

Defined in: [WAProto/index.d.ts:7045](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7045)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`attachmentType`](../interfaces/IInvoiceMessage.md#attachmenttype)

***

### note?

> `optional` **note**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7043](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7043)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`note`](../interfaces/IInvoiceMessage.md#note)

***

### token?

> `optional` **token**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7044](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7044)

#### Implementation of

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md).[`token`](../interfaces/IInvoiceMessage.md#token)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7058](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7058)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:7053](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7053)

#### Parameters

##### properties?

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:7055](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7055)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7054](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7054)

#### Parameters

##### m

[`IInvoiceMessage`](../interfaces/IInvoiceMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InvoiceMessage`](InvoiceMessage.md)

Defined in: [WAProto/index.d.ts:7056](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7056)

#### Parameters

##### d

#### Returns

[`InvoiceMessage`](InvoiceMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7059](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7059)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7057](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7057)

#### Parameters

##### m

[`InvoiceMessage`](InvoiceMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
