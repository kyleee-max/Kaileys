# Class: Option

Defined in: [WAProto/index.d.ts:8337](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8337)

## Implements

- [`IOption`](../interfaces/IOption.md)

## Constructors

### new Option()

> **new Option**(`p`?): [`Option`](Option.md)

Defined in: [WAProto/index.d.ts:8338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8338)

#### Parameters

##### p?

[`IOption`](../interfaces/IOption.md)

#### Returns

[`Option`](Option.md)

## Properties

### optionHash?

> `optional` **optionHash**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8340)

#### Implementation of

[`IOption`](../interfaces/IOption.md).[`optionHash`](../interfaces/IOption.md#optionhash)

***

### optionName?

> `optional` **optionName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8339)

#### Implementation of

[`IOption`](../interfaces/IOption.md).[`optionName`](../interfaces/IOption.md#optionname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8346](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8346)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Option`](Option.md)

Defined in: [WAProto/index.d.ts:8341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8341)

#### Parameters

##### properties?

[`IOption`](../interfaces/IOption.md)

#### Returns

[`Option`](Option.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Option`](Option.md)

Defined in: [WAProto/index.d.ts:8343](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8343)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Option`](Option.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8342)

#### Parameters

##### m

[`IOption`](../interfaces/IOption.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Option`](Option.md)

Defined in: [WAProto/index.d.ts:8344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8344)

#### Parameters

##### d

#### Returns

[`Option`](Option.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8347)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8345)

#### Parameters

##### m

[`Option`](Option.md)

##### o?

`IConversionOptions`

#### Returns

`object`
