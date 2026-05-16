# Class: TransformerArg

Defined in: [WAProto/index.d.ts:13360](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13360)

## Implements

- [`ITransformerArg`](../interfaces/ITransformerArg.md)

## Constructors

### new TransformerArg()

> **new TransformerArg**(`p`?): [`TransformerArg`](TransformerArg.md)

Defined in: [WAProto/index.d.ts:13361](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13361)

#### Parameters

##### p?

[`ITransformerArg`](../interfaces/ITransformerArg.md)

#### Returns

[`TransformerArg`](TransformerArg.md)

## Properties

### key?

> `optional` **key**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13362](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13362)

#### Implementation of

[`ITransformerArg`](../interfaces/ITransformerArg.md).[`key`](../interfaces/ITransformerArg.md#key)

***

### value?

> `optional` **value**: `null` \| [`IValue`](../namespaces/TransformerArg/interfaces/IValue.md)

Defined in: [WAProto/index.d.ts:13363](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13363)

#### Implementation of

[`ITransformerArg`](../interfaces/ITransformerArg.md).[`value`](../interfaces/ITransformerArg.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13369](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13369)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`TransformerArg`](TransformerArg.md)

Defined in: [WAProto/index.d.ts:13364](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13364)

#### Parameters

##### properties?

[`ITransformerArg`](../interfaces/ITransformerArg.md)

#### Returns

[`TransformerArg`](TransformerArg.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`TransformerArg`](TransformerArg.md)

Defined in: [WAProto/index.d.ts:13366](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13366)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`TransformerArg`](TransformerArg.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13365](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13365)

#### Parameters

##### m

[`ITransformerArg`](../interfaces/ITransformerArg.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`TransformerArg`](TransformerArg.md)

Defined in: [WAProto/index.d.ts:13367](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13367)

#### Parameters

##### d

#### Returns

[`TransformerArg`](TransformerArg.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13370)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13368](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13368)

#### Parameters

##### m

[`TransformerArg`](TransformerArg.md)

##### o?

`IConversionOptions`

#### Returns

`object`
