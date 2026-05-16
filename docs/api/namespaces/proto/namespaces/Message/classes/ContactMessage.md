# Class: ContactMessage

Defined in: [WAProto/index.d.ts:5963](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5963)

## Implements

- [`IContactMessage`](../interfaces/IContactMessage.md)

## Constructors

### new ContactMessage()

> **new ContactMessage**(`p`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:5964](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5964)

#### Parameters

##### p?

[`IContactMessage`](../interfaces/IContactMessage.md)

#### Returns

[`ContactMessage`](ContactMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:5967](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5967)

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`contextInfo`](../interfaces/IContactMessage.md#contextinfo)

***

### displayName?

> `optional` **displayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5965](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5965)

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`displayName`](../interfaces/IContactMessage.md#displayname)

***

### vcard?

> `optional` **vcard**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5966](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5966)

#### Implementation of

[`IContactMessage`](../interfaces/IContactMessage.md).[`vcard`](../interfaces/IContactMessage.md#vcard)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5973)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:5968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5968)

#### Parameters

##### properties?

[`IContactMessage`](../interfaces/IContactMessage.md)

#### Returns

[`ContactMessage`](ContactMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:5970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5970)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ContactMessage`](ContactMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5969)

#### Parameters

##### m

[`IContactMessage`](../interfaces/IContactMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ContactMessage`](ContactMessage.md)

Defined in: [WAProto/index.d.ts:5971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5971)

#### Parameters

##### d

#### Returns

[`ContactMessage`](ContactMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5974)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5972)

#### Parameters

##### m

[`ContactMessage`](ContactMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
