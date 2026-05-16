# Class: PaymentLinkHeader

Defined in: [WAProto/index.d.ts:7706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7706)

## Implements

- [`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

## Constructors

### new PaymentLinkHeader()

> **new PaymentLinkHeader**(`p`?): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:7707](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7707)

#### Parameters

##### p?

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

## Properties

### headerType?

> `optional` **headerType**: `null` \| [`PaymentLinkHeaderType`](../namespaces/PaymentLinkHeader/enumerations/PaymentLinkHeaderType.md)

Defined in: [WAProto/index.d.ts:7708](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7708)

#### Implementation of

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md).[`headerType`](../interfaces/IPaymentLinkHeader.md#headertype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7714](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7714)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:7709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7709)

#### Parameters

##### properties?

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:7711](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7711)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7710](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7710)

#### Parameters

##### m

[`IPaymentLinkHeader`](../interfaces/IPaymentLinkHeader.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentLinkHeader`](PaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:7712](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7712)

#### Parameters

##### d

#### Returns

[`PaymentLinkHeader`](PaymentLinkHeader.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7715](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7715)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7713](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7713)

#### Parameters

##### m

[`PaymentLinkHeader`](PaymentLinkHeader.md)

##### o?

`IConversionOptions`

#### Returns

`object`
