# Class: CancelPaymentRequestMessage

Defined in: [WAProto/index.d.ts:5856](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5856)

## Implements

- [`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

## Constructors

### new CancelPaymentRequestMessage()

> **new CancelPaymentRequestMessage**(`p`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:5857](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5857)

#### Parameters

##### p?

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:5858](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5858)

#### Implementation of

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md).[`key`](../interfaces/ICancelPaymentRequestMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5864](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5864)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:5859](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5859)

#### Parameters

##### properties?

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:5861](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5861)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5860](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5860)

#### Parameters

##### m

[`ICancelPaymentRequestMessage`](../interfaces/ICancelPaymentRequestMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:5862](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5862)

#### Parameters

##### d

#### Returns

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5865](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5865)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5863](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5863)

#### Parameters

##### m

[`CancelPaymentRequestMessage`](CancelPaymentRequestMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
