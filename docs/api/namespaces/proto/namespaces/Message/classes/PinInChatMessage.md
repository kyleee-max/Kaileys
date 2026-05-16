# Class: PinInChatMessage

Defined in: [WAProto/index.d.ts:8248](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8248)

## Implements

- [`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

## Constructors

### new PinInChatMessage()

> **new PinInChatMessage**(`p`?): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:8249](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8249)

#### Parameters

##### p?

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8250](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8250)

#### Implementation of

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md).[`key`](../interfaces/IPinInChatMessage.md#key)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8252](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8252)

#### Implementation of

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md).[`senderTimestampMs`](../interfaces/IPinInChatMessage.md#sendertimestampms)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/PinInChatMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:8251](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8251)

#### Implementation of

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md).[`type`](../interfaces/IPinInChatMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8258](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8258)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:8253](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8253)

#### Parameters

##### properties?

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:8255](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8255)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8254](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8254)

#### Parameters

##### m

[`IPinInChatMessage`](../interfaces/IPinInChatMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PinInChatMessage`](PinInChatMessage.md)

Defined in: [WAProto/index.d.ts:8256](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8256)

#### Parameters

##### d

#### Returns

[`PinInChatMessage`](PinInChatMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8259](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8259)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8257](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8257)

#### Parameters

##### m

[`PinInChatMessage`](PinInChatMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
