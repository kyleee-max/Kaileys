# Class: ContactAction

Defined in: [WAProto/index.d.ts:11821](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11821)

## Implements

- [`IContactAction`](../interfaces/IContactAction.md)

## Constructors

### new ContactAction()

> **new ContactAction**(`p`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:11822](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11822)

#### Parameters

##### p?

[`IContactAction`](../interfaces/IContactAction.md)

#### Returns

[`ContactAction`](ContactAction.md)

## Properties

### firstName?

> `optional` **firstName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11824)

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`firstName`](../interfaces/IContactAction.md#firstname)

***

### fullName?

> `optional` **fullName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11823](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11823)

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`fullName`](../interfaces/IContactAction.md#fullname)

***

### lidJid?

> `optional` **lidJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11825)

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`lidJid`](../interfaces/IContactAction.md#lidjid)

***

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11827)

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`pnJid`](../interfaces/IContactAction.md#pnjid)

***

### saveOnPrimaryAddressbook?

> `optional` **saveOnPrimaryAddressbook**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11826)

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`saveOnPrimaryAddressbook`](../interfaces/IContactAction.md#saveonprimaryaddressbook)

***

### username?

> `optional` **username**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11828)

#### Implementation of

[`IContactAction`](../interfaces/IContactAction.md).[`username`](../interfaces/IContactAction.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11834)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:11829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11829)

#### Parameters

##### properties?

[`IContactAction`](../interfaces/IContactAction.md)

#### Returns

[`ContactAction`](ContactAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:11831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11831)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ContactAction`](ContactAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11830)

#### Parameters

##### m

[`IContactAction`](../interfaces/IContactAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ContactAction`](ContactAction.md)

Defined in: [WAProto/index.d.ts:11832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11832)

#### Parameters

##### d

#### Returns

[`ContactAction`](ContactAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11835)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11833)

#### Parameters

##### m

[`ContactAction`](ContactAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
