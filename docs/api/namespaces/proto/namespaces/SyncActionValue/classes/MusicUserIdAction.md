# Class: MusicUserIdAction

Defined in: [WAProto/index.d.ts:12329](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12329)

## Implements

- [`IMusicUserIdAction`](../interfaces/IMusicUserIdAction.md)

## Constructors

### new MusicUserIdAction()

> **new MusicUserIdAction**(`p`?): [`MusicUserIdAction`](MusicUserIdAction.md)

Defined in: [WAProto/index.d.ts:12330](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12330)

#### Parameters

##### p?

[`IMusicUserIdAction`](../interfaces/IMusicUserIdAction.md)

#### Returns

[`MusicUserIdAction`](MusicUserIdAction.md)

## Properties

### musicUserId?

> `optional` **musicUserId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12331](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12331)

#### Implementation of

[`IMusicUserIdAction`](../interfaces/IMusicUserIdAction.md).[`musicUserId`](../interfaces/IMusicUserIdAction.md#musicuserid)

***

### musicUserIdMap

> **musicUserIdMap**: `object`

Defined in: [WAProto/index.d.ts:12332](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12332)

#### Index Signature

\[`k`: `string`\]: `string`

#### Implementation of

[`IMusicUserIdAction`](../interfaces/IMusicUserIdAction.md).[`musicUserIdMap`](../interfaces/IMusicUserIdAction.md#musicuseridmap)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12338)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MusicUserIdAction`](MusicUserIdAction.md)

Defined in: [WAProto/index.d.ts:12333](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12333)

#### Parameters

##### properties?

[`IMusicUserIdAction`](../interfaces/IMusicUserIdAction.md)

#### Returns

[`MusicUserIdAction`](MusicUserIdAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MusicUserIdAction`](MusicUserIdAction.md)

Defined in: [WAProto/index.d.ts:12335](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12335)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MusicUserIdAction`](MusicUserIdAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12334](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12334)

#### Parameters

##### m

[`IMusicUserIdAction`](../interfaces/IMusicUserIdAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MusicUserIdAction`](MusicUserIdAction.md)

Defined in: [WAProto/index.d.ts:12336](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12336)

#### Parameters

##### d

#### Returns

[`MusicUserIdAction`](MusicUserIdAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12339)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12337](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12337)

#### Parameters

##### m

[`MusicUserIdAction`](MusicUserIdAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
