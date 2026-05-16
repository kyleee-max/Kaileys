# Class: EmbeddedContent

Defined in: [WAProto/index.d.ts:4044](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4044)

## Implements

- [`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

## Constructors

### new EmbeddedContent()

> **new EmbeddedContent**(`p`?): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:4045](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4045)

#### Parameters

##### p?

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

## Properties

### content?

> `optional` **content**: `"embeddedMessage"` \| `"embeddedMusic"`

Defined in: [WAProto/index.d.ts:4048](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4048)

***

### embeddedMessage?

> `optional` **embeddedMessage**: `null` \| [`IEmbeddedMessage`](../interfaces/IEmbeddedMessage.md)

Defined in: [WAProto/index.d.ts:4046](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4046)

#### Implementation of

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md).[`embeddedMessage`](../interfaces/IEmbeddedContent.md#embeddedmessage)

***

### embeddedMusic?

> `optional` **embeddedMusic**: `null` \| [`IEmbeddedMusic`](../interfaces/IEmbeddedMusic.md)

Defined in: [WAProto/index.d.ts:4047](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4047)

#### Implementation of

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md).[`embeddedMusic`](../interfaces/IEmbeddedContent.md#embeddedmusic)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4054](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4054)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:4049](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4049)

#### Parameters

##### properties?

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:4051](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4051)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4050](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4050)

#### Parameters

##### m

[`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EmbeddedContent`](EmbeddedContent.md)

Defined in: [WAProto/index.d.ts:4052](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4052)

#### Parameters

##### d

#### Returns

[`EmbeddedContent`](EmbeddedContent.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4055](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4055)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4053](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4053)

#### Parameters

##### m

[`EmbeddedContent`](EmbeddedContent.md)

##### o?

`IConversionOptions`

#### Returns

`object`
