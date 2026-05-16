# Class: EncReactionMessage

Defined in: [WAProto/index.d.ts:6137](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6137)

## Implements

- [`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

## Constructors

### new EncReactionMessage()

> **new EncReactionMessage**(`p`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:6138](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6138)

#### Parameters

##### p?

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6141](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6141)

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`encIv`](../interfaces/IEncReactionMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6140](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6140)

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`encPayload`](../interfaces/IEncReactionMessage.md#encpayload)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:6139](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6139)

#### Implementation of

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md).[`targetMessageKey`](../interfaces/IEncReactionMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6147](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6147)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:6142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6142)

#### Parameters

##### properties?

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:6144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6144)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6143](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6143)

#### Parameters

##### m

[`IEncReactionMessage`](../interfaces/IEncReactionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EncReactionMessage`](EncReactionMessage.md)

Defined in: [WAProto/index.d.ts:6145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6145)

#### Parameters

##### d

#### Returns

[`EncReactionMessage`](EncReactionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6148](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6148)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6146](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6146)

#### Parameters

##### m

[`EncReactionMessage`](EncReactionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
