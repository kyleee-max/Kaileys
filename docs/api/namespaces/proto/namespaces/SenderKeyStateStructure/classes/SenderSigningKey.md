# Class: SenderSigningKey

Defined in: [WAProto/index.d.ts:10844](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10844)

## Implements

- [`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

## Constructors

### new SenderSigningKey()

> **new SenderSigningKey**(`p`?): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:10845](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10845)

#### Parameters

##### p?

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

## Properties

### private?

> `optional` **private**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10847](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10847)

#### Implementation of

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md).[`private`](../interfaces/ISenderSigningKey.md#private)

***

### public?

> `optional` **public**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10846](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10846)

#### Implementation of

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md).[`public`](../interfaces/ISenderSigningKey.md#public)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10853](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10853)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:10848](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10848)

#### Parameters

##### properties?

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:10850](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10850)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10849](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10849)

#### Parameters

##### m

[`ISenderSigningKey`](../interfaces/ISenderSigningKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderSigningKey`](SenderSigningKey.md)

Defined in: [WAProto/index.d.ts:10851](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10851)

#### Parameters

##### d

#### Returns

[`SenderSigningKey`](SenderSigningKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10854](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10854)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10852](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10852)

#### Parameters

##### m

[`SenderSigningKey`](SenderSigningKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
