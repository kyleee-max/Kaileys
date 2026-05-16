# Class: GroupStatus

Defined in: [WAProto/index.d.ts:11201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11201)

## Implements

- [`IGroupStatus`](../interfaces/IGroupStatus.md)

## Constructors

### new GroupStatus()

> **new GroupStatus**(`p`?): [`GroupStatus`](GroupStatus.md)

Defined in: [WAProto/index.d.ts:11202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11202)

#### Parameters

##### p?

[`IGroupStatus`](../interfaces/IGroupStatus.md)

#### Returns

[`GroupStatus`](GroupStatus.md)

## Properties

### authorJid?

> `optional` **authorJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11203)

#### Implementation of

[`IGroupStatus`](../interfaces/IGroupStatus.md).[`authorJid`](../interfaces/IGroupStatus.md#authorjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11209](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11209)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GroupStatus`](GroupStatus.md)

Defined in: [WAProto/index.d.ts:11204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11204)

#### Parameters

##### properties?

[`IGroupStatus`](../interfaces/IGroupStatus.md)

#### Returns

[`GroupStatus`](GroupStatus.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GroupStatus`](GroupStatus.md)

Defined in: [WAProto/index.d.ts:11206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11206)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GroupStatus`](GroupStatus.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11205)

#### Parameters

##### m

[`IGroupStatus`](../interfaces/IGroupStatus.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GroupStatus`](GroupStatus.md)

Defined in: [WAProto/index.d.ts:11207](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11207)

#### Parameters

##### d

#### Returns

[`GroupStatus`](GroupStatus.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11210](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11210)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11208](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11208)

#### Parameters

##### m

[`GroupStatus`](GroupStatus.md)

##### o?

`IConversionOptions`

#### Returns

`object`
