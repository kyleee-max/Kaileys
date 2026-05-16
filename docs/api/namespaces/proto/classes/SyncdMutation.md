# Class: SyncdMutation

Defined in: [WAProto/index.d.ts:13011](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13011)

## Implements

- [`ISyncdMutation`](../interfaces/ISyncdMutation.md)

## Constructors

### new SyncdMutation()

> **new SyncdMutation**(`p`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:13012](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13012)

#### Parameters

##### p?

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

#### Returns

[`SyncdMutation`](SyncdMutation.md)

## Properties

### operation?

> `optional` **operation**: `null` \| [`SyncdOperation`](../namespaces/SyncdMutation/enumerations/SyncdOperation.md)

Defined in: [WAProto/index.d.ts:13013](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13013)

#### Implementation of

[`ISyncdMutation`](../interfaces/ISyncdMutation.md).[`operation`](../interfaces/ISyncdMutation.md#operation)

***

### record?

> `optional` **record**: `null` \| [`ISyncdRecord`](../interfaces/ISyncdRecord.md)

Defined in: [WAProto/index.d.ts:13014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13014)

#### Implementation of

[`ISyncdMutation`](../interfaces/ISyncdMutation.md).[`record`](../interfaces/ISyncdMutation.md#record)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13020)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:13015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13015)

#### Parameters

##### properties?

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

#### Returns

[`SyncdMutation`](SyncdMutation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:13017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13017)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdMutation`](SyncdMutation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13016)

#### Parameters

##### m

[`ISyncdMutation`](../interfaces/ISyncdMutation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdMutation`](SyncdMutation.md)

Defined in: [WAProto/index.d.ts:13018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13018)

#### Parameters

##### d

#### Returns

[`SyncdMutation`](SyncdMutation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13021)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13019)

#### Parameters

##### m

[`SyncdMutation`](SyncdMutation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
