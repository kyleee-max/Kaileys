# Class: SendPaymentMessage

Defined in: [WAProto/index.d.ts:8851](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8851)

## Implements

- [`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

## Constructors

### new SendPaymentMessage()

> **new SendPaymentMessage**(`p`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8852](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8852)

#### Parameters

##### p?

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

## Properties

### background?

> `optional` **background**: `null` \| [`IPaymentBackground`](../../../interfaces/IPaymentBackground.md)

Defined in: [WAProto/index.d.ts:8855](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8855)

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`background`](../interfaces/ISendPaymentMessage.md#background)

***

### noteMessage?

> `optional` **noteMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:8853](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8853)

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`noteMessage`](../interfaces/ISendPaymentMessage.md#notemessage)

***

### requestMessageKey?

> `optional` **requestMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8854](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8854)

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`requestMessageKey`](../interfaces/ISendPaymentMessage.md#requestmessagekey)

***

### transactionData?

> `optional` **transactionData**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8856](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8856)

#### Implementation of

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md).[`transactionData`](../interfaces/ISendPaymentMessage.md#transactiondata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8862](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8862)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8857](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8857)

#### Parameters

##### properties?

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8859](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8859)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8858](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8858)

#### Parameters

##### m

[`ISendPaymentMessage`](../interfaces/ISendPaymentMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SendPaymentMessage`](SendPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8860](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8860)

#### Parameters

##### d

#### Returns

[`SendPaymentMessage`](SendPaymentMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8863](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8863)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8861](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8861)

#### Parameters

##### m

[`SendPaymentMessage`](SendPaymentMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
