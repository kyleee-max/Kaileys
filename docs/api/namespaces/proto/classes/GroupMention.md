# Class: GroupMention

Defined in: [WAProto/index.d.ts:4386](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4386)

## Implements

- [`IGroupMention`](../interfaces/IGroupMention.md)

## Constructors

### new GroupMention()

> **new GroupMention**(`p`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:4387](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4387)

#### Parameters

##### p?

[`IGroupMention`](../interfaces/IGroupMention.md)

#### Returns

[`GroupMention`](GroupMention.md)

## Properties

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4388](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4388)

#### Implementation of

[`IGroupMention`](../interfaces/IGroupMention.md).[`groupJid`](../interfaces/IGroupMention.md#groupjid)

***

### groupSubject?

> `optional` **groupSubject**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4389](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4389)

#### Implementation of

[`IGroupMention`](../interfaces/IGroupMention.md).[`groupSubject`](../interfaces/IGroupMention.md#groupsubject)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4395](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4395)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:4390](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4390)

#### Parameters

##### properties?

[`IGroupMention`](../interfaces/IGroupMention.md)

#### Returns

[`GroupMention`](GroupMention.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:4392](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4392)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GroupMention`](GroupMention.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4391](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4391)

#### Parameters

##### m

[`IGroupMention`](../interfaces/IGroupMention.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GroupMention`](GroupMention.md)

Defined in: [WAProto/index.d.ts:4393](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4393)

#### Parameters

##### d

#### Returns

[`GroupMention`](GroupMention.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4396](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4396)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4394](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4394)

#### Parameters

##### m

[`GroupMention`](GroupMention.md)

##### o?

`IConversionOptions`

#### Returns

`object`
