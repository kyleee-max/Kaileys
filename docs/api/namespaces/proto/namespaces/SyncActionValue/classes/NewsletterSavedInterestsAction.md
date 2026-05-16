# Class: NewsletterSavedInterestsAction

Defined in: [WAProto/index.d.ts:12366](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12366)

## Implements

- [`INewsletterSavedInterestsAction`](../interfaces/INewsletterSavedInterestsAction.md)

## Constructors

### new NewsletterSavedInterestsAction()

> **new NewsletterSavedInterestsAction**(`p`?): [`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

Defined in: [WAProto/index.d.ts:12367](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12367)

#### Parameters

##### p?

[`INewsletterSavedInterestsAction`](../interfaces/INewsletterSavedInterestsAction.md)

#### Returns

[`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

## Properties

### newsletterSavedInterests?

> `optional` **newsletterSavedInterests**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12368](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12368)

#### Implementation of

[`INewsletterSavedInterestsAction`](../interfaces/INewsletterSavedInterestsAction.md).[`newsletterSavedInterests`](../interfaces/INewsletterSavedInterestsAction.md#newslettersavedinterests)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12374](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12374)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

Defined in: [WAProto/index.d.ts:12369](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12369)

#### Parameters

##### properties?

[`INewsletterSavedInterestsAction`](../interfaces/INewsletterSavedInterestsAction.md)

#### Returns

[`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

Defined in: [WAProto/index.d.ts:12371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12371)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12370)

#### Parameters

##### m

[`INewsletterSavedInterestsAction`](../interfaces/INewsletterSavedInterestsAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

Defined in: [WAProto/index.d.ts:12372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12372)

#### Parameters

##### d

#### Returns

[`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12375](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12375)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12373)

#### Parameters

##### m

[`NewsletterSavedInterestsAction`](NewsletterSavedInterestsAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
