# Class: PaymentLinkProvider

Defined in: [WAProto/index.d.ts:7730](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7730)

## Implements

- [`IPaymentLinkProvider`](../interfaces/IPaymentLinkProvider.md)

## Constructors

### new PaymentLinkProvider()

> **new PaymentLinkProvider**(`p`?): [`PaymentLinkProvider`](PaymentLinkProvider.md)

Defined in: [WAProto/index.d.ts:7731](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7731)

#### Parameters

##### p?

[`IPaymentLinkProvider`](../interfaces/IPaymentLinkProvider.md)

#### Returns

[`PaymentLinkProvider`](PaymentLinkProvider.md)

## Properties

### paramsJson?

> `optional` **paramsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7732](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7732)

#### Implementation of

[`IPaymentLinkProvider`](../interfaces/IPaymentLinkProvider.md).[`paramsJson`](../interfaces/IPaymentLinkProvider.md#paramsjson)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7738](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7738)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkProvider`](PaymentLinkProvider.md)

Defined in: [WAProto/index.d.ts:7733](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7733)

#### Parameters

##### properties?

[`IPaymentLinkProvider`](../interfaces/IPaymentLinkProvider.md)

#### Returns

[`PaymentLinkProvider`](PaymentLinkProvider.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentLinkProvider`](PaymentLinkProvider.md)

Defined in: [WAProto/index.d.ts:7735](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7735)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentLinkProvider`](PaymentLinkProvider.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7734](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7734)

#### Parameters

##### m

[`IPaymentLinkProvider`](../interfaces/IPaymentLinkProvider.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentLinkProvider`](PaymentLinkProvider.md)

Defined in: [WAProto/index.d.ts:7736](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7736)

#### Parameters

##### d

#### Returns

[`PaymentLinkProvider`](PaymentLinkProvider.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7739)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7737](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7737)

#### Parameters

##### m

[`PaymentLinkProvider`](PaymentLinkProvider.md)

##### o?

`IConversionOptions`

#### Returns

`object`
