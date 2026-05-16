# Class: EncEventResponseMessage

Defined in: [WAProto/index.d.ts:6117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6117)

## Implements

- [`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

## Constructors

### new EncEventResponseMessage()

> **new EncEventResponseMessage**(`p`?): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6118)

#### Parameters

##### p?

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6121)

#### Implementation of

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md).[`encIv`](../interfaces/IEncEventResponseMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6120)

#### Implementation of

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md).[`encPayload`](../interfaces/IEncEventResponseMessage.md#encpayload)

***

### eventCreationMessageKey?

> `optional` **eventCreationMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:6119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6119)

#### Implementation of

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md).[`eventCreationMessageKey`](../interfaces/IEncEventResponseMessage.md#eventcreationmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6127)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6122](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6122)

#### Parameters

##### properties?

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6124)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6123)

#### Parameters

##### m

[`IEncEventResponseMessage`](../interfaces/IEncEventResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EncEventResponseMessage`](EncEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6125)

#### Parameters

##### d

#### Returns

[`EncEventResponseMessage`](EncEventResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6128](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6128)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6126)

#### Parameters

##### m

[`EncEventResponseMessage`](EncEventResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
