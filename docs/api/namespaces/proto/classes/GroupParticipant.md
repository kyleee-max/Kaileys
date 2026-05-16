# Class: GroupParticipant

Defined in: [WAProto/index.d.ts:4405](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4405)

## Implements

- [`IGroupParticipant`](../interfaces/IGroupParticipant.md)

## Constructors

### new GroupParticipant()

> **new GroupParticipant**(`p`?): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:4406](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4406)

#### Parameters

##### p?

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

#### Returns

[`GroupParticipant`](GroupParticipant.md)

## Properties

### memberLabel?

> `optional` **memberLabel**: `null` \| [`IMemberLabel`](../interfaces/IMemberLabel.md)

Defined in: [WAProto/index.d.ts:4409](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4409)

#### Implementation of

[`IGroupParticipant`](../interfaces/IGroupParticipant.md).[`memberLabel`](../interfaces/IGroupParticipant.md#memberlabel)

***

### rank?

> `optional` **rank**: `null` \| [`Rank`](../namespaces/GroupParticipant/enumerations/Rank.md)

Defined in: [WAProto/index.d.ts:4408](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4408)

#### Implementation of

[`IGroupParticipant`](../interfaces/IGroupParticipant.md).[`rank`](../interfaces/IGroupParticipant.md#rank)

***

### userJid

> **userJid**: `string`

Defined in: [WAProto/index.d.ts:4407](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4407)

#### Implementation of

[`IGroupParticipant`](../interfaces/IGroupParticipant.md).[`userJid`](../interfaces/IGroupParticipant.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4415)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:4410](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4410)

#### Parameters

##### properties?

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

#### Returns

[`GroupParticipant`](GroupParticipant.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:4412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4412)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GroupParticipant`](GroupParticipant.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4411](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4411)

#### Parameters

##### m

[`IGroupParticipant`](../interfaces/IGroupParticipant.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GroupParticipant`](GroupParticipant.md)

Defined in: [WAProto/index.d.ts:4413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4413)

#### Parameters

##### d

#### Returns

[`GroupParticipant`](GroupParticipant.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4416)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4414)

#### Parameters

##### m

[`GroupParticipant`](GroupParticipant.md)

##### o?

`IConversionOptions`

#### Returns

`object`
