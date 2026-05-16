# Class: SyncdVersion

Defined in: [WAProto/index.d.ts:13142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13142)

## Implements

- [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

## Constructors

### new SyncdVersion()

> **new SyncdVersion**(`p`?): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:13143](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13143)

#### Parameters

##### p?

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

#### Returns

[`SyncdVersion`](SyncdVersion.md)

## Properties

### version?

> `optional` **version**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13144)

#### Implementation of

[`ISyncdVersion`](../interfaces/ISyncdVersion.md).[`version`](../interfaces/ISyncdVersion.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13150](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13150)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:13145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13145)

#### Parameters

##### properties?

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

#### Returns

[`SyncdVersion`](SyncdVersion.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:13147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13147)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdVersion`](SyncdVersion.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13146)

#### Parameters

##### m

[`ISyncdVersion`](../interfaces/ISyncdVersion.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdVersion`](SyncdVersion.md)

Defined in: [WAProto/index.d.ts:13148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13148)

#### Parameters

##### d

#### Returns

[`SyncdVersion`](SyncdVersion.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13151](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13151)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13149](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13149)

#### Parameters

##### m

[`SyncdVersion`](SyncdVersion.md)

##### o?

`IConversionOptions`

#### Returns

`object`
