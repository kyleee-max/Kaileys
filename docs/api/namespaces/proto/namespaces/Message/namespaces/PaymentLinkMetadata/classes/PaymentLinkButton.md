# Class: PaymentLinkButton

Defined in: [WAProto/index.d.ts:7690](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7690)

## Implements

- [`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

## Constructors

### new PaymentLinkButton()

> **new PaymentLinkButton**(`p`?): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:7691](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7691)

#### Parameters

##### p?

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7692](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7692)

#### Implementation of

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md).[`displayText`](../interfaces/IPaymentLinkButton.md#displaytext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7698](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7698)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:7693](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7693)

#### Parameters

##### properties?

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:7695](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7695)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7694](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7694)

#### Parameters

##### m

[`IPaymentLinkButton`](../interfaces/IPaymentLinkButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentLinkButton`](PaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:7696](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7696)

#### Parameters

##### d

#### Returns

[`PaymentLinkButton`](PaymentLinkButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7699)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7697](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7697)

#### Parameters

##### m

[`PaymentLinkButton`](PaymentLinkButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
