# Class: Footer

Defined in: [WAProto/index.d.ts:6838](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6838)

## Implements

- [`IFooter`](../interfaces/IFooter.md)

## Constructors

### new Footer()

> **new Footer**(`p`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:6839](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6839)

#### Parameters

##### p?

[`IFooter`](../interfaces/IFooter.md)

#### Returns

[`Footer`](Footer.md)

## Properties

### audioMessage?

> `optional` **audioMessage**: `null` \| [`IAudioMessage`](../../../interfaces/IAudioMessage.md)

Defined in: [WAProto/index.d.ts:6842](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6842)

#### Implementation of

[`IFooter`](../interfaces/IFooter.md).[`audioMessage`](../interfaces/IFooter.md#audiomessage)

***

### hasMediaAttachment?

> `optional` **hasMediaAttachment**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6841](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6841)

#### Implementation of

[`IFooter`](../interfaces/IFooter.md).[`hasMediaAttachment`](../interfaces/IFooter.md#hasmediaattachment)

***

### media?

> `optional` **media**: `"audioMessage"`

Defined in: [WAProto/index.d.ts:6843](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6843)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6840](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6840)

#### Implementation of

[`IFooter`](../interfaces/IFooter.md).[`text`](../interfaces/IFooter.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6849](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6849)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:6844](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6844)

#### Parameters

##### properties?

[`IFooter`](../interfaces/IFooter.md)

#### Returns

[`Footer`](Footer.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:6846](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6846)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Footer`](Footer.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6845](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6845)

#### Parameters

##### m

[`IFooter`](../interfaces/IFooter.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Footer`](Footer.md)

Defined in: [WAProto/index.d.ts:6847](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6847)

#### Parameters

##### d

#### Returns

[`Footer`](Footer.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6850](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6850)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6848](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6848)

#### Parameters

##### m

[`Footer`](Footer.md)

##### o?

`IConversionOptions`

#### Returns

`object`
