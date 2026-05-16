# Class: SyncdSnapshot

Defined in: [WAProto/index.d.ts:13107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13107)

## Implements

- [`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

## Constructors

### new SyncdSnapshot()

> **new SyncdSnapshot**(`p`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:13108](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13108)

#### Parameters

##### p?

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

## Properties

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:13112](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13112)

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`keyId`](../interfaces/ISyncdSnapshot.md#keyid)

***

### mac?

> `optional` **mac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13111](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13111)

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`mac`](../interfaces/ISyncdSnapshot.md#mac)

***

### records

> **records**: [`ISyncdRecord`](../interfaces/ISyncdRecord.md)[]

Defined in: [WAProto/index.d.ts:13110](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13110)

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`records`](../interfaces/ISyncdSnapshot.md#records)

***

### version?

> `optional` **version**: `null` \| [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Defined in: [WAProto/index.d.ts:13109](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13109)

#### Implementation of

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md).[`version`](../interfaces/ISyncdSnapshot.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13118)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:13113](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13113)

#### Parameters

##### properties?

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:13115](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13115)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13114](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13114)

#### Parameters

##### m

[`ISyncdSnapshot`](../interfaces/ISyncdSnapshot.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdSnapshot`](SyncdSnapshot.md)

Defined in: [WAProto/index.d.ts:13116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13116)

#### Parameters

##### d

#### Returns

[`SyncdSnapshot`](SyncdSnapshot.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13119)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13117)

#### Parameters

##### m

[`SyncdSnapshot`](SyncdSnapshot.md)

##### o?

`IConversionOptions`

#### Returns

`object`
