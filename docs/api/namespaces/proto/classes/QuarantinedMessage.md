# Class: QuarantinedMessage

Defined in: [WAProto/index.d.ts:10610](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10610)

## Implements

- [`IQuarantinedMessage`](../interfaces/IQuarantinedMessage.md)

## Constructors

### new QuarantinedMessage()

> **new QuarantinedMessage**(`p`?): [`QuarantinedMessage`](QuarantinedMessage.md)

Defined in: [WAProto/index.d.ts:10611](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10611)

#### Parameters

##### p?

[`IQuarantinedMessage`](../interfaces/IQuarantinedMessage.md)

#### Returns

[`QuarantinedMessage`](QuarantinedMessage.md)

## Properties

### extractedText?

> `optional` **extractedText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10613](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10613)

#### Implementation of

[`IQuarantinedMessage`](../interfaces/IQuarantinedMessage.md).[`extractedText`](../interfaces/IQuarantinedMessage.md#extractedtext)

***

### originalData?

> `optional` **originalData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10612](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10612)

#### Implementation of

[`IQuarantinedMessage`](../interfaces/IQuarantinedMessage.md).[`originalData`](../interfaces/IQuarantinedMessage.md#originaldata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10619](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10619)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`QuarantinedMessage`](QuarantinedMessage.md)

Defined in: [WAProto/index.d.ts:10614](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10614)

#### Parameters

##### properties?

[`IQuarantinedMessage`](../interfaces/IQuarantinedMessage.md)

#### Returns

[`QuarantinedMessage`](QuarantinedMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`QuarantinedMessage`](QuarantinedMessage.md)

Defined in: [WAProto/index.d.ts:10616](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10616)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`QuarantinedMessage`](QuarantinedMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10615](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10615)

#### Parameters

##### m

[`IQuarantinedMessage`](../interfaces/IQuarantinedMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`QuarantinedMessage`](QuarantinedMessage.md)

Defined in: [WAProto/index.d.ts:10617](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10617)

#### Parameters

##### d

#### Returns

[`QuarantinedMessage`](QuarantinedMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10620](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10620)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10618](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10618)

#### Parameters

##### m

[`QuarantinedMessage`](QuarantinedMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
