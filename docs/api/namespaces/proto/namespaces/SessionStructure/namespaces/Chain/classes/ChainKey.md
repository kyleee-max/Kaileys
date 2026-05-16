# Class: ChainKey

Defined in: [WAProto/index.d.ts:10945](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10945)

## Implements

- [`IChainKey`](../interfaces/IChainKey.md)

## Constructors

### new ChainKey()

> **new ChainKey**(`p`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:10946](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10946)

#### Parameters

##### p?

[`IChainKey`](../interfaces/IChainKey.md)

#### Returns

[`ChainKey`](ChainKey.md)

## Properties

### index?

> `optional` **index**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10947](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10947)

#### Implementation of

[`IChainKey`](../interfaces/IChainKey.md).[`index`](../interfaces/IChainKey.md#index)

***

### key?

> `optional` **key**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10948)

#### Implementation of

[`IChainKey`](../interfaces/IChainKey.md).[`key`](../interfaces/IChainKey.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10954)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:10949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10949)

#### Parameters

##### properties?

[`IChainKey`](../interfaces/IChainKey.md)

#### Returns

[`ChainKey`](ChainKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:10951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10951)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ChainKey`](ChainKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10950)

#### Parameters

##### m

[`IChainKey`](../interfaces/IChainKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ChainKey`](ChainKey.md)

Defined in: [WAProto/index.d.ts:10952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10952)

#### Parameters

##### d

#### Returns

[`ChainKey`](ChainKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10955)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10953)

#### Parameters

##### m

[`ChainKey`](ChainKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
