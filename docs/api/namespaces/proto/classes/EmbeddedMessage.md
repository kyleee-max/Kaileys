# Class: EmbeddedMessage

Defined in: [WAProto/index.d.ts:4063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4063)

## Implements

- [`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

## Constructors

### new EmbeddedMessage()

> **new EmbeddedMessage**(`p`?): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:4064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4064)

#### Parameters

##### p?

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:4066](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4066)

#### Implementation of

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md).[`message`](../interfaces/IEmbeddedMessage.md#message)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4065)

#### Implementation of

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md).[`stanzaId`](../interfaces/IEmbeddedMessage.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4072)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:4067](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4067)

#### Parameters

##### properties?

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:4069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4069)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4068](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4068)

#### Parameters

##### m

[`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EmbeddedMessage`](EmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:4070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4070)

#### Parameters

##### d

#### Returns

[`EmbeddedMessage`](EmbeddedMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4073](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4073)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4071](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4071)

#### Parameters

##### m

[`EmbeddedMessage`](EmbeddedMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
