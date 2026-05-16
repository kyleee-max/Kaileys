# Class: StatusQuotedMessage

Defined in: [WAProto/index.d.ts:8939](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8939)

## Implements

- [`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md)

## Constructors

### new StatusQuotedMessage()

> **new StatusQuotedMessage**(`p`?): [`StatusQuotedMessage`](StatusQuotedMessage.md)

Defined in: [WAProto/index.d.ts:8940](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8940)

#### Parameters

##### p?

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md)

#### Returns

[`StatusQuotedMessage`](StatusQuotedMessage.md)

## Properties

### originalStatusId?

> `optional` **originalStatusId**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8944](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8944)

#### Implementation of

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md).[`originalStatusId`](../interfaces/IStatusQuotedMessage.md#originalstatusid)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8942](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8942)

#### Implementation of

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md).[`text`](../interfaces/IStatusQuotedMessage.md#text)

***

### thumbnail?

> `optional` **thumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8943](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8943)

#### Implementation of

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md).[`thumbnail`](../interfaces/IStatusQuotedMessage.md#thumbnail)

***

### type?

> `optional` **type**: `null` \| [`QUESTION_ANSWER`](../namespaces/StatusQuotedMessage/enumerations/StatusQuotedMessageType.md#question_answer)

Defined in: [WAProto/index.d.ts:8941](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8941)

#### Implementation of

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md).[`type`](../interfaces/IStatusQuotedMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8950)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusQuotedMessage`](StatusQuotedMessage.md)

Defined in: [WAProto/index.d.ts:8945](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8945)

#### Parameters

##### properties?

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md)

#### Returns

[`StatusQuotedMessage`](StatusQuotedMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusQuotedMessage`](StatusQuotedMessage.md)

Defined in: [WAProto/index.d.ts:8947](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8947)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusQuotedMessage`](StatusQuotedMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8946](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8946)

#### Parameters

##### m

[`IStatusQuotedMessage`](../interfaces/IStatusQuotedMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusQuotedMessage`](StatusQuotedMessage.md)

Defined in: [WAProto/index.d.ts:8948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8948)

#### Parameters

##### d

#### Returns

[`StatusQuotedMessage`](StatusQuotedMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8951)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8949)

#### Parameters

##### m

[`StatusQuotedMessage`](StatusQuotedMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
