# Class: NewsletterFollowerInviteMessage

Defined in: [WAProto/index.d.ts:7543](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7543)

## Implements

- [`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md)

## Constructors

### new NewsletterFollowerInviteMessage()

> **new NewsletterFollowerInviteMessage**(`p`?): [`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

Defined in: [WAProto/index.d.ts:7544](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7544)

#### Parameters

##### p?

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md)

#### Returns

[`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7548](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7548)

#### Implementation of

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md).[`caption`](../interfaces/INewsletterFollowerInviteMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7549](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7549)

#### Implementation of

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md).[`contextInfo`](../interfaces/INewsletterFollowerInviteMessage.md#contextinfo)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7547](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7547)

#### Implementation of

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md).[`jpegThumbnail`](../interfaces/INewsletterFollowerInviteMessage.md#jpegthumbnail)

***

### newsletterJid?

> `optional` **newsletterJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7545](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7545)

#### Implementation of

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md).[`newsletterJid`](../interfaces/INewsletterFollowerInviteMessage.md#newsletterjid)

***

### newsletterName?

> `optional` **newsletterName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7546](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7546)

#### Implementation of

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md).[`newsletterName`](../interfaces/INewsletterFollowerInviteMessage.md#newslettername)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7555](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7555)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

Defined in: [WAProto/index.d.ts:7550](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7550)

#### Parameters

##### properties?

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md)

#### Returns

[`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

Defined in: [WAProto/index.d.ts:7552](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7552)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7551](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7551)

#### Parameters

##### m

[`INewsletterFollowerInviteMessage`](../interfaces/INewsletterFollowerInviteMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

Defined in: [WAProto/index.d.ts:7553](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7553)

#### Parameters

##### d

#### Returns

[`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7556](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7556)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7554](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7554)

#### Parameters

##### m

[`NewsletterFollowerInviteMessage`](NewsletterFollowerInviteMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
