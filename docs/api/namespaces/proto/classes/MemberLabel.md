# Class: MemberLabel

Defined in: [WAProto/index.d.ts:5172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5172)

## Implements

- [`IMemberLabel`](../interfaces/IMemberLabel.md)

## Constructors

### new MemberLabel()

> **new MemberLabel**(`p`?): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:5173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5173)

#### Parameters

##### p?

[`IMemberLabel`](../interfaces/IMemberLabel.md)

#### Returns

[`MemberLabel`](MemberLabel.md)

## Properties

### label?

> `optional` **label**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5174)

#### Implementation of

[`IMemberLabel`](../interfaces/IMemberLabel.md).[`label`](../interfaces/IMemberLabel.md#label)

***

### labelTimestamp?

> `optional` **labelTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5175)

#### Implementation of

[`IMemberLabel`](../interfaces/IMemberLabel.md).[`labelTimestamp`](../interfaces/IMemberLabel.md#labeltimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5181)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:5176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5176)

#### Parameters

##### properties?

[`IMemberLabel`](../interfaces/IMemberLabel.md)

#### Returns

[`MemberLabel`](MemberLabel.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:5178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5178)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MemberLabel`](MemberLabel.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5177)

#### Parameters

##### m

[`IMemberLabel`](../interfaces/IMemberLabel.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MemberLabel`](MemberLabel.md)

Defined in: [WAProto/index.d.ts:5179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5179)

#### Parameters

##### d

#### Returns

[`MemberLabel`](MemberLabel.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5182)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5180)

#### Parameters

##### m

[`MemberLabel`](MemberLabel.md)

##### o?

`IConversionOptions`

#### Returns

`object`
