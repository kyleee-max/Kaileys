# Class: LidContactAction

Defined in: [WAProto/index.d.ts:12154](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12154)

## Implements

- [`ILidContactAction`](../interfaces/ILidContactAction.md)

## Constructors

### new LidContactAction()

> **new LidContactAction**(`p`?): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:12155](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12155)

#### Parameters

##### p?

[`ILidContactAction`](../interfaces/ILidContactAction.md)

#### Returns

[`LidContactAction`](LidContactAction.md)

## Properties

### firstName?

> `optional` **firstName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12157](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12157)

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`firstName`](../interfaces/ILidContactAction.md#firstname)

***

### fullName?

> `optional` **fullName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12156](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12156)

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`fullName`](../interfaces/ILidContactAction.md#fullname)

***

### username?

> `optional` **username**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12158](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12158)

#### Implementation of

[`ILidContactAction`](../interfaces/ILidContactAction.md).[`username`](../interfaces/ILidContactAction.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12164](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12164)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:12159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12159)

#### Parameters

##### properties?

[`ILidContactAction`](../interfaces/ILidContactAction.md)

#### Returns

[`LidContactAction`](LidContactAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:12161](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12161)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LidContactAction`](LidContactAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12160](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12160)

#### Parameters

##### m

[`ILidContactAction`](../interfaces/ILidContactAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LidContactAction`](LidContactAction.md)

Defined in: [WAProto/index.d.ts:12162](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12162)

#### Parameters

##### d

#### Returns

[`LidContactAction`](LidContactAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12165)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12163](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12163)

#### Parameters

##### m

[`LidContactAction`](LidContactAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
