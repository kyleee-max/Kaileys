# Class: EncCommentMessage

Defined in: [WAProto/index.d.ts:6097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6097)

## Implements

- [`IEncCommentMessage`](../interfaces/IEncCommentMessage.md)

## Constructors

### new EncCommentMessage()

> **new EncCommentMessage**(`p`?): [`EncCommentMessage`](EncCommentMessage.md)

Defined in: [WAProto/index.d.ts:6098](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6098)

#### Parameters

##### p?

[`IEncCommentMessage`](../interfaces/IEncCommentMessage.md)

#### Returns

[`EncCommentMessage`](EncCommentMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6101](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6101)

#### Implementation of

[`IEncCommentMessage`](../interfaces/IEncCommentMessage.md).[`encIv`](../interfaces/IEncCommentMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6100](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6100)

#### Implementation of

[`IEncCommentMessage`](../interfaces/IEncCommentMessage.md).[`encPayload`](../interfaces/IEncCommentMessage.md#encpayload)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:6099](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6099)

#### Implementation of

[`IEncCommentMessage`](../interfaces/IEncCommentMessage.md).[`targetMessageKey`](../interfaces/IEncCommentMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6107)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EncCommentMessage`](EncCommentMessage.md)

Defined in: [WAProto/index.d.ts:6102](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6102)

#### Parameters

##### properties?

[`IEncCommentMessage`](../interfaces/IEncCommentMessage.md)

#### Returns

[`EncCommentMessage`](EncCommentMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EncCommentMessage`](EncCommentMessage.md)

Defined in: [WAProto/index.d.ts:6104](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6104)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EncCommentMessage`](EncCommentMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6103](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6103)

#### Parameters

##### m

[`IEncCommentMessage`](../interfaces/IEncCommentMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EncCommentMessage`](EncCommentMessage.md)

Defined in: [WAProto/index.d.ts:6105](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6105)

#### Parameters

##### d

#### Returns

[`EncCommentMessage`](EncCommentMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6108](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6108)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6106](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6106)

#### Parameters

##### m

[`EncCommentMessage`](EncCommentMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
