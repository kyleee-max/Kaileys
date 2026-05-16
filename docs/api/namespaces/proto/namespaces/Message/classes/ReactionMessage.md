# Class: ReactionMessage

Defined in: [WAProto/index.d.ts:8675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8675)

## Implements

- [`IReactionMessage`](../interfaces/IReactionMessage.md)

## Constructors

### new ReactionMessage()

> **new ReactionMessage**(`p`?): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:8676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8676)

#### Parameters

##### p?

[`IReactionMessage`](../interfaces/IReactionMessage.md)

#### Returns

[`ReactionMessage`](ReactionMessage.md)

## Properties

### groupingKey?

> `optional` **groupingKey**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8679)

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`groupingKey`](../interfaces/IReactionMessage.md#groupingkey)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8677)

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`key`](../interfaces/IReactionMessage.md#key)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8680)

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`senderTimestampMs`](../interfaces/IReactionMessage.md#sendertimestampms)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8678)

#### Implementation of

[`IReactionMessage`](../interfaces/IReactionMessage.md).[`text`](../interfaces/IReactionMessage.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8686](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8686)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:8681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8681)

#### Parameters

##### properties?

[`IReactionMessage`](../interfaces/IReactionMessage.md)

#### Returns

[`ReactionMessage`](ReactionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:8683](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8683)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ReactionMessage`](ReactionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8682)

#### Parameters

##### m

[`IReactionMessage`](../interfaces/IReactionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ReactionMessage`](ReactionMessage.md)

Defined in: [WAProto/index.d.ts:8684](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8684)

#### Parameters

##### d

#### Returns

[`ReactionMessage`](ReactionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8687](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8687)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8685](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8685)

#### Parameters

##### m

[`ReactionMessage`](ReactionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
