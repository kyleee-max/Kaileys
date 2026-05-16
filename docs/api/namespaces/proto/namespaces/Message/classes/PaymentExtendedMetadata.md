# Class: PaymentExtendedMetadata

Defined in: [WAProto/index.d.ts:7622](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7622)

## Implements

- [`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md)

## Constructors

### new PaymentExtendedMetadata()

> **new PaymentExtendedMetadata**(`p`?): [`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

Defined in: [WAProto/index.d.ts:7623](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7623)

#### Parameters

##### p?

[`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md)

#### Returns

[`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

## Properties

### messageParamsJson?

> `optional` **messageParamsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7626](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7626)

#### Implementation of

[`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md).[`messageParamsJson`](../interfaces/IPaymentExtendedMetadata.md#messageparamsjson)

***

### platform?

> `optional` **platform**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7625](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7625)

#### Implementation of

[`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md).[`platform`](../interfaces/IPaymentExtendedMetadata.md#platform)

***

### type?

> `optional` **type**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7624](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7624)

#### Implementation of

[`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md).[`type`](../interfaces/IPaymentExtendedMetadata.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7632](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7632)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

Defined in: [WAProto/index.d.ts:7627](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7627)

#### Parameters

##### properties?

[`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md)

#### Returns

[`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

Defined in: [WAProto/index.d.ts:7629](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7629)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7628](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7628)

#### Parameters

##### m

[`IPaymentExtendedMetadata`](../interfaces/IPaymentExtendedMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

Defined in: [WAProto/index.d.ts:7630](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7630)

#### Parameters

##### d

#### Returns

[`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7633](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7633)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7631](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7631)

#### Parameters

##### m

[`PaymentExtendedMetadata`](PaymentExtendedMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
