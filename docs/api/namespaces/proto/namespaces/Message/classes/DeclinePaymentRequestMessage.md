# Class: DeclinePaymentRequestMessage

Defined in: [WAProto/index.d.ts:6001](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6001)

## Implements

- [`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

## Constructors

### new DeclinePaymentRequestMessage()

> **new DeclinePaymentRequestMessage**(`p`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:6002](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6002)

#### Parameters

##### p?

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:6003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6003)

#### Implementation of

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md).[`key`](../interfaces/IDeclinePaymentRequestMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6009](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6009)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:6004](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6004)

#### Parameters

##### properties?

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:6006](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6006)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6005)

#### Parameters

##### m

[`IDeclinePaymentRequestMessage`](../interfaces/IDeclinePaymentRequestMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

Defined in: [WAProto/index.d.ts:6007](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6007)

#### Parameters

##### d

#### Returns

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6010](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6010)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6008](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6008)

#### Parameters

##### m

[`DeclinePaymentRequestMessage`](DeclinePaymentRequestMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
