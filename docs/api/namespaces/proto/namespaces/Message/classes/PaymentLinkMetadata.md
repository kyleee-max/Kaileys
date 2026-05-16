# Class: PaymentLinkMetadata

Defined in: [WAProto/index.d.ts:7670](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7670)

## Implements

- [`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

## Constructors

### new PaymentLinkMetadata()

> **new PaymentLinkMetadata**(`p`?): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:7671](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7671)

#### Parameters

##### p?

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

## Properties

### button?

> `optional` **button**: `null` \| [`IPaymentLinkButton`](../namespaces/PaymentLinkMetadata/interfaces/IPaymentLinkButton.md)

Defined in: [WAProto/index.d.ts:7672](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7672)

#### Implementation of

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md).[`button`](../interfaces/IPaymentLinkMetadata.md#button)

***

### header?

> `optional` **header**: `null` \| [`IPaymentLinkHeader`](../namespaces/PaymentLinkMetadata/interfaces/IPaymentLinkHeader.md)

Defined in: [WAProto/index.d.ts:7673](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7673)

#### Implementation of

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md).[`header`](../interfaces/IPaymentLinkMetadata.md#header)

***

### provider?

> `optional` **provider**: `null` \| [`IPaymentLinkProvider`](../namespaces/PaymentLinkMetadata/interfaces/IPaymentLinkProvider.md)

Defined in: [WAProto/index.d.ts:7674](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7674)

#### Implementation of

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md).[`provider`](../interfaces/IPaymentLinkMetadata.md#provider)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7680)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:7675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7675)

#### Parameters

##### properties?

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:7677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7677)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7676)

#### Parameters

##### m

[`IPaymentLinkMetadata`](../interfaces/IPaymentLinkMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentLinkMetadata`](PaymentLinkMetadata.md)

Defined in: [WAProto/index.d.ts:7678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7678)

#### Parameters

##### d

#### Returns

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7681)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7679)

#### Parameters

##### m

[`PaymentLinkMetadata`](PaymentLinkMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
