# Class: KeepInChat

Defined in: [WAProto/index.d.ts:4886](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4886)

## Implements

- [`IKeepInChat`](../interfaces/IKeepInChat.md)

## Constructors

### new KeepInChat()

> **new KeepInChat**(`p`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:4887](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4887)

#### Parameters

##### p?

[`IKeepInChat`](../interfaces/IKeepInChat.md)

#### Returns

[`KeepInChat`](KeepInChat.md)

## Properties

### clientTimestampMs?

> `optional` **clientTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4892](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4892)

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`clientTimestampMs`](../interfaces/IKeepInChat.md#clienttimestampms)

***

### deviceJid?

> `optional` **deviceJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4891](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4891)

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`deviceJid`](../interfaces/IKeepInChat.md#devicejid)

***

### keepType?

> `optional` **keepType**: `null` \| [`KeepType`](../enumerations/KeepType.md)

Defined in: [WAProto/index.d.ts:4888](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4888)

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`keepType`](../interfaces/IKeepInChat.md#keeptype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:4890](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4890)

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`key`](../interfaces/IKeepInChat.md#key)

***

### serverTimestamp?

> `optional` **serverTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4889](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4889)

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`serverTimestamp`](../interfaces/IKeepInChat.md#servertimestamp)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4893](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4893)

#### Implementation of

[`IKeepInChat`](../interfaces/IKeepInChat.md).[`serverTimestampMs`](../interfaces/IKeepInChat.md#servertimestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4899)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:4894](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4894)

#### Parameters

##### properties?

[`IKeepInChat`](../interfaces/IKeepInChat.md)

#### Returns

[`KeepInChat`](KeepInChat.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:4896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4896)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`KeepInChat`](KeepInChat.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4895](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4895)

#### Parameters

##### m

[`IKeepInChat`](../interfaces/IKeepInChat.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`KeepInChat`](KeepInChat.md)

Defined in: [WAProto/index.d.ts:4897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4897)

#### Parameters

##### d

#### Returns

[`KeepInChat`](KeepInChat.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4900)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4898)

#### Parameters

##### m

[`KeepInChat`](KeepInChat.md)

##### o?

`IConversionOptions`

#### Returns

`object`
