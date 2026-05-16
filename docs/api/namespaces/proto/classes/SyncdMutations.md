# Class: SyncdMutations

Defined in: [WAProto/index.d.ts:13036](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13036)

## Implements

- [`ISyncdMutations`](../interfaces/ISyncdMutations.md)

## Constructors

### new SyncdMutations()

> **new SyncdMutations**(`p`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:13037](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13037)

#### Parameters

##### p?

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

#### Returns

[`SyncdMutations`](SyncdMutations.md)

## Properties

### mutations

> **mutations**: [`ISyncdMutation`](../interfaces/ISyncdMutation.md)[]

Defined in: [WAProto/index.d.ts:13038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13038)

#### Implementation of

[`ISyncdMutations`](../interfaces/ISyncdMutations.md).[`mutations`](../interfaces/ISyncdMutations.md#mutations)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13044](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13044)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:13039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13039)

#### Parameters

##### properties?

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

#### Returns

[`SyncdMutations`](SyncdMutations.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:13041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13041)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdMutations`](SyncdMutations.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13040)

#### Parameters

##### m

[`ISyncdMutations`](../interfaces/ISyncdMutations.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdMutations`](SyncdMutations.md)

Defined in: [WAProto/index.d.ts:13042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13042)

#### Parameters

##### d

#### Returns

[`SyncdMutations`](SyncdMutations.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13045](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13045)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13043](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13043)

#### Parameters

##### m

[`SyncdMutations`](SyncdMutations.md)

##### o?

`IConversionOptions`

#### Returns

`object`
