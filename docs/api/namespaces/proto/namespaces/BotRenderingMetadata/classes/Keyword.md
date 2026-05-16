# Class: Keyword

Defined in: [WAProto/index.d.ts:2072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2072)

## Implements

- [`IKeyword`](../interfaces/IKeyword.md)

## Constructors

### new Keyword()

> **new Keyword**(`p`?): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:2073](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2073)

#### Parameters

##### p?

[`IKeyword`](../interfaces/IKeyword.md)

#### Returns

[`Keyword`](Keyword.md)

## Properties

### associatedPrompts

> **associatedPrompts**: `string`[]

Defined in: [WAProto/index.d.ts:2075](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2075)

#### Implementation of

[`IKeyword`](../interfaces/IKeyword.md).[`associatedPrompts`](../interfaces/IKeyword.md#associatedprompts)

***

### value?

> `optional` **value**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2074](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2074)

#### Implementation of

[`IKeyword`](../interfaces/IKeyword.md).[`value`](../interfaces/IKeyword.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2081](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2081)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:2076](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2076)

#### Parameters

##### properties?

[`IKeyword`](../interfaces/IKeyword.md)

#### Returns

[`Keyword`](Keyword.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:2078](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2078)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Keyword`](Keyword.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2077](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2077)

#### Parameters

##### m

[`IKeyword`](../interfaces/IKeyword.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Keyword`](Keyword.md)

Defined in: [WAProto/index.d.ts:2079](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2079)

#### Parameters

##### d

#### Returns

[`Keyword`](Keyword.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2082](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2082)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2080](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2080)

#### Parameters

##### m

[`Keyword`](Keyword.md)

##### o?

`IConversionOptions`

#### Returns

`object`
