# Class: LegacyMessage

Defined in: [WAProto/index.d.ts:5008](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5008)

## Implements

- [`ILegacyMessage`](../interfaces/ILegacyMessage.md)

## Constructors

### new LegacyMessage()

> **new LegacyMessage**(`p`?): [`LegacyMessage`](LegacyMessage.md)

Defined in: [WAProto/index.d.ts:5009](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5009)

#### Parameters

##### p?

[`ILegacyMessage`](../interfaces/ILegacyMessage.md)

#### Returns

[`LegacyMessage`](LegacyMessage.md)

## Properties

### eventResponseMessage?

> `optional` **eventResponseMessage**: `null` \| [`IEventResponseMessage`](../namespaces/Message/interfaces/IEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:5010](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5010)

#### Implementation of

[`ILegacyMessage`](../interfaces/ILegacyMessage.md).[`eventResponseMessage`](../interfaces/ILegacyMessage.md#eventresponsemessage)

***

### pollVote?

> `optional` **pollVote**: `null` \| [`IPollVoteMessage`](../namespaces/Message/interfaces/IPollVoteMessage.md)

Defined in: [WAProto/index.d.ts:5011](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5011)

#### Implementation of

[`ILegacyMessage`](../interfaces/ILegacyMessage.md).[`pollVote`](../interfaces/ILegacyMessage.md#pollvote)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5017)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LegacyMessage`](LegacyMessage.md)

Defined in: [WAProto/index.d.ts:5012](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5012)

#### Parameters

##### properties?

[`ILegacyMessage`](../interfaces/ILegacyMessage.md)

#### Returns

[`LegacyMessage`](LegacyMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LegacyMessage`](LegacyMessage.md)

Defined in: [WAProto/index.d.ts:5014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5014)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LegacyMessage`](LegacyMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5013](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5013)

#### Parameters

##### m

[`ILegacyMessage`](../interfaces/ILegacyMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LegacyMessage`](LegacyMessage.md)

Defined in: [WAProto/index.d.ts:5015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5015)

#### Parameters

##### d

#### Returns

[`LegacyMessage`](LegacyMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5018)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5016)

#### Parameters

##### m

[`LegacyMessage`](LegacyMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
