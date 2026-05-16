# Class: MuteAction

Defined in: [WAProto/index.d.ts:12348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12348)

## Implements

- [`IMuteAction`](../interfaces/IMuteAction.md)

## Constructors

### new MuteAction()

> **new MuteAction**(`p`?): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:12349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12349)

#### Parameters

##### p?

[`IMuteAction`](../interfaces/IMuteAction.md)

#### Returns

[`MuteAction`](MuteAction.md)

## Properties

### autoMuted?

> `optional` **autoMuted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12352](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12352)

#### Implementation of

[`IMuteAction`](../interfaces/IMuteAction.md).[`autoMuted`](../interfaces/IMuteAction.md#automuted)

***

### muted?

> `optional` **muted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12350)

#### Implementation of

[`IMuteAction`](../interfaces/IMuteAction.md).[`muted`](../interfaces/IMuteAction.md#muted)

***

### muteEndTimestamp?

> `optional` **muteEndTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12351)

#### Implementation of

[`IMuteAction`](../interfaces/IMuteAction.md).[`muteEndTimestamp`](../interfaces/IMuteAction.md#muteendtimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12358](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12358)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:12353](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12353)

#### Parameters

##### properties?

[`IMuteAction`](../interfaces/IMuteAction.md)

#### Returns

[`MuteAction`](MuteAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:12355](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12355)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MuteAction`](MuteAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12354](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12354)

#### Parameters

##### m

[`IMuteAction`](../interfaces/IMuteAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MuteAction`](MuteAction.md)

Defined in: [WAProto/index.d.ts:12356](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12356)

#### Parameters

##### d

#### Returns

[`MuteAction`](MuteAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12359](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12359)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12357](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12357)

#### Parameters

##### m

[`MuteAction`](MuteAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
