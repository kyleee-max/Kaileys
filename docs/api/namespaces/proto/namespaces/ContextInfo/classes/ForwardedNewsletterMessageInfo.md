# Class: ForwardedNewsletterMessageInfo

Defined in: [WAProto/index.d.ts:3479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3479)

## Implements

- [`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

## Constructors

### new ForwardedNewsletterMessageInfo()

> **new ForwardedNewsletterMessageInfo**(`p`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:3480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3480)

#### Parameters

##### p?

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

## Properties

### accessibilityText?

> `optional` **accessibilityText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3485)

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`accessibilityText`](../interfaces/IForwardedNewsletterMessageInfo.md#accessibilitytext)

***

### contentType?

> `optional` **contentType**: `null` \| [`ContentType`](../namespaces/ForwardedNewsletterMessageInfo/enumerations/ContentType.md)

Defined in: [WAProto/index.d.ts:3484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3484)

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`contentType`](../interfaces/IForwardedNewsletterMessageInfo.md#contenttype)

***

### newsletterJid?

> `optional` **newsletterJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3481)

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`newsletterJid`](../interfaces/IForwardedNewsletterMessageInfo.md#newsletterjid)

***

### newsletterName?

> `optional` **newsletterName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3483)

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`newsletterName`](../interfaces/IForwardedNewsletterMessageInfo.md#newslettername)

***

### serverMessageId?

> `optional` **serverMessageId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3482)

#### Implementation of

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md).[`serverMessageId`](../interfaces/IForwardedNewsletterMessageInfo.md#servermessageid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3491](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3491)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:3486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3486)

#### Parameters

##### properties?

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:3488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3488)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3487)

#### Parameters

##### m

[`IForwardedNewsletterMessageInfo`](../interfaces/IForwardedNewsletterMessageInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:3489](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3489)

#### Parameters

##### d

#### Returns

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3492](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3492)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3490](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3490)

#### Parameters

##### m

[`ForwardedNewsletterMessageInfo`](ForwardedNewsletterMessageInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
