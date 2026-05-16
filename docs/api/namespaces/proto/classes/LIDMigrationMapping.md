# Class: LIDMigrationMapping

Defined in: [WAProto/index.d.ts:4955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4955)

## Implements

- [`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

## Constructors

### new LIDMigrationMapping()

> **new LIDMigrationMapping**(`p`?): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:4956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4956)

#### Parameters

##### p?

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

## Properties

### assignedLid

> **assignedLid**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:4958](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4958)

#### Implementation of

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md).[`assignedLid`](../interfaces/ILIDMigrationMapping.md#assignedlid)

***

### latestLid?

> `optional` **latestLid**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4959](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4959)

#### Implementation of

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md).[`latestLid`](../interfaces/ILIDMigrationMapping.md#latestlid)

***

### pn

> **pn**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:4957](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4957)

#### Implementation of

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md).[`pn`](../interfaces/ILIDMigrationMapping.md#pn)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4965](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4965)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:4960](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4960)

#### Parameters

##### properties?

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:4962](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4962)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4961](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4961)

#### Parameters

##### m

[`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LIDMigrationMapping`](LIDMigrationMapping.md)

Defined in: [WAProto/index.d.ts:4963](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4963)

#### Parameters

##### d

#### Returns

[`LIDMigrationMapping`](LIDMigrationMapping.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4966](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4966)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4964](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4964)

#### Parameters

##### m

[`LIDMigrationMapping`](LIDMigrationMapping.md)

##### o?

`IConversionOptions`

#### Returns

`object`
