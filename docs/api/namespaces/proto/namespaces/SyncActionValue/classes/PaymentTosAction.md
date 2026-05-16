# Class: PaymentTosAction

Defined in: [WAProto/index.d.ts:12473](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12473)

## Implements

- [`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

## Constructors

### new PaymentTosAction()

> **new PaymentTosAction**(`p`?): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:12474](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12474)

#### Parameters

##### p?

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

## Properties

### accepted

> **accepted**: `boolean`

Defined in: [WAProto/index.d.ts:12476](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12476)

#### Implementation of

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md).[`accepted`](../interfaces/IPaymentTosAction.md#accepted)

***

### paymentNotice

> **paymentNotice**: [`BR_PAY_PRIVACY_POLICY`](../namespaces/PaymentTosAction/enumerations/PaymentNotice.md#br_pay_privacy_policy)

Defined in: [WAProto/index.d.ts:12475](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12475)

#### Implementation of

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md).[`paymentNotice`](../interfaces/IPaymentTosAction.md#paymentnotice)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12482)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:12477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12477)

#### Parameters

##### properties?

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:12479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12479)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12478)

#### Parameters

##### m

[`IPaymentTosAction`](../interfaces/IPaymentTosAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentTosAction`](PaymentTosAction.md)

Defined in: [WAProto/index.d.ts:12480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12480)

#### Parameters

##### d

#### Returns

[`PaymentTosAction`](PaymentTosAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12483)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12481)

#### Parameters

##### m

[`PaymentTosAction`](PaymentTosAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
