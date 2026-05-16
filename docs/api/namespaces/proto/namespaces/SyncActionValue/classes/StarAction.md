# Class: StarAction

Defined in: [WAProto/index.d.ts:12706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12706)

## Implements

- [`IStarAction`](../interfaces/IStarAction.md)

## Constructors

### new StarAction()

> **new StarAction**(`p`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:12707](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12707)

#### Parameters

##### p?

[`IStarAction`](../interfaces/IStarAction.md)

#### Returns

[`StarAction`](StarAction.md)

## Properties

### starred?

> `optional` **starred**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12708](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12708)

#### Implementation of

[`IStarAction`](../interfaces/IStarAction.md).[`starred`](../interfaces/IStarAction.md#starred)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12714](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12714)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:12709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12709)

#### Parameters

##### properties?

[`IStarAction`](../interfaces/IStarAction.md)

#### Returns

[`StarAction`](StarAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:12711](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12711)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StarAction`](StarAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12710](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12710)

#### Parameters

##### m

[`IStarAction`](../interfaces/IStarAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StarAction`](StarAction.md)

Defined in: [WAProto/index.d.ts:12712](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12712)

#### Parameters

##### d

#### Returns

[`StarAction`](StarAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12715](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12715)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12713](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12713)

#### Parameters

##### m

[`StarAction`](StarAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
