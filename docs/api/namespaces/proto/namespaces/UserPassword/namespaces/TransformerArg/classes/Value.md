# Class: Value

Defined in: [WAProto/index.d.ts:13380](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13380)

## Implements

- [`IValue`](../interfaces/IValue.md)

## Constructors

### new Value()

> **new Value**(`p`?): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:13381](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13381)

#### Parameters

##### p?

[`IValue`](../interfaces/IValue.md)

#### Returns

[`Value`](Value.md)

## Properties

### asBlob?

> `optional` **asBlob**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13382](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13382)

#### Implementation of

[`IValue`](../interfaces/IValue.md).[`asBlob`](../interfaces/IValue.md#asblob)

***

### asUnsignedInteger?

> `optional` **asUnsignedInteger**: `null` \| `number`

Defined in: [WAProto/index.d.ts:13383](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13383)

#### Implementation of

[`IValue`](../interfaces/IValue.md).[`asUnsignedInteger`](../interfaces/IValue.md#asunsignedinteger)

***

### value?

> `optional` **value**: `"asBlob"` \| `"asUnsignedInteger"`

Defined in: [WAProto/index.d.ts:13384](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13384)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13390](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13390)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:13385](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13385)

#### Parameters

##### properties?

[`IValue`](../interfaces/IValue.md)

#### Returns

[`Value`](Value.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:13387](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13387)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Value`](Value.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13386](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13386)

#### Parameters

##### m

[`IValue`](../interfaces/IValue.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Value`](Value.md)

Defined in: [WAProto/index.d.ts:13388](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13388)

#### Parameters

##### d

#### Returns

[`Value`](Value.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13391](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13391)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13389](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13389)

#### Parameters

##### m

[`Value`](Value.md)

##### o?

`IConversionOptions`

#### Returns

`object`
