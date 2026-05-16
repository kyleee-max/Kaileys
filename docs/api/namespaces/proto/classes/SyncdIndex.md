# Class: SyncdIndex

Defined in: [WAProto/index.d.ts:12994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12994)

## Implements

- [`ISyncdIndex`](../interfaces/ISyncdIndex.md)

## Constructors

### new SyncdIndex()

> **new SyncdIndex**(`p`?): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:12995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12995)

#### Parameters

##### p?

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

#### Returns

[`SyncdIndex`](SyncdIndex.md)

## Properties

### blob?

> `optional` **blob**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:12996](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12996)

#### Implementation of

[`ISyncdIndex`](../interfaces/ISyncdIndex.md).[`blob`](../interfaces/ISyncdIndex.md#blob)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13002](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13002)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:12997](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12997)

#### Parameters

##### properties?

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

#### Returns

[`SyncdIndex`](SyncdIndex.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:12999](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12999)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdIndex`](SyncdIndex.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12998](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12998)

#### Parameters

##### m

[`ISyncdIndex`](../interfaces/ISyncdIndex.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdIndex`](SyncdIndex.md)

Defined in: [WAProto/index.d.ts:13000](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13000)

#### Parameters

##### d

#### Returns

[`SyncdIndex`](SyncdIndex.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13003)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13001](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13001)

#### Parameters

##### m

[`SyncdIndex`](SyncdIndex.md)

##### o?

`IConversionOptions`

#### Returns

`object`
