# Class: UserPassword

Defined in: [WAProto/index.d.ts:13327](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13327)

## Implements

- [`IUserPassword`](../interfaces/IUserPassword.md)

## Constructors

### new UserPassword()

> **new UserPassword**(`p`?): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:13328](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13328)

#### Parameters

##### p?

[`IUserPassword`](../interfaces/IUserPassword.md)

#### Returns

[`UserPassword`](UserPassword.md)

## Properties

### encoding?

> `optional` **encoding**: `null` \| [`Encoding`](../namespaces/UserPassword/enumerations/Encoding.md)

Defined in: [WAProto/index.d.ts:13329](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13329)

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`encoding`](../interfaces/IUserPassword.md#encoding)

***

### transformedData?

> `optional` **transformedData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13332](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13332)

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`transformedData`](../interfaces/IUserPassword.md#transformeddata)

***

### transformer?

> `optional` **transformer**: `null` \| [`Transformer`](../namespaces/UserPassword/enumerations/Transformer.md)

Defined in: [WAProto/index.d.ts:13330](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13330)

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`transformer`](../interfaces/IUserPassword.md#transformer)

***

### transformerArg

> **transformerArg**: [`ITransformerArg`](../namespaces/UserPassword/interfaces/ITransformerArg.md)[]

Defined in: [WAProto/index.d.ts:13331](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13331)

#### Implementation of

[`IUserPassword`](../interfaces/IUserPassword.md).[`transformerArg`](../interfaces/IUserPassword.md#transformerarg)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13338)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:13333](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13333)

#### Parameters

##### properties?

[`IUserPassword`](../interfaces/IUserPassword.md)

#### Returns

[`UserPassword`](UserPassword.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:13335](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13335)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UserPassword`](UserPassword.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13334](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13334)

#### Parameters

##### m

[`IUserPassword`](../interfaces/IUserPassword.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UserPassword`](UserPassword.md)

Defined in: [WAProto/index.d.ts:13336](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13336)

#### Parameters

##### d

#### Returns

[`UserPassword`](UserPassword.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13339)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13337](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13337)

#### Parameters

##### m

[`UserPassword`](UserPassword.md)

##### o?

`IConversionOptions`

#### Returns

`object`
