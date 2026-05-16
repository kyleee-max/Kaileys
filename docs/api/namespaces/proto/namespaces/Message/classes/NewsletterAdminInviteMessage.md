# Class: NewsletterAdminInviteMessage

Defined in: [WAProto/index.d.ts:7518](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7518)

## Implements

- [`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

## Constructors

### new NewsletterAdminInviteMessage()

> **new NewsletterAdminInviteMessage**(`p`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:7519](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7519)

#### Parameters

##### p?

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7523](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7523)

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`caption`](../interfaces/INewsletterAdminInviteMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7525](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7525)

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`contextInfo`](../interfaces/INewsletterAdminInviteMessage.md#contextinfo)

***

### inviteExpiration?

> `optional` **inviteExpiration**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7524](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7524)

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`inviteExpiration`](../interfaces/INewsletterAdminInviteMessage.md#inviteexpiration)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7522](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7522)

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`jpegThumbnail`](../interfaces/INewsletterAdminInviteMessage.md#jpegthumbnail)

***

### newsletterJid?

> `optional` **newsletterJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7520](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7520)

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`newsletterJid`](../interfaces/INewsletterAdminInviteMessage.md#newsletterjid)

***

### newsletterName?

> `optional` **newsletterName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7521](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7521)

#### Implementation of

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md).[`newsletterName`](../interfaces/INewsletterAdminInviteMessage.md#newslettername)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7531](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7531)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:7526](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7526)

#### Parameters

##### properties?

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:7528](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7528)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7527](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7527)

#### Parameters

##### m

[`INewsletterAdminInviteMessage`](../interfaces/INewsletterAdminInviteMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

Defined in: [WAProto/index.d.ts:7529](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7529)

#### Parameters

##### d

#### Returns

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7532](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7532)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7530](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7530)

#### Parameters

##### m

[`NewsletterAdminInviteMessage`](NewsletterAdminInviteMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
