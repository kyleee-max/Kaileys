# Class: PaymentLinkPreviewMetadata

Defined in: [WAProto/index.d.ts:8159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8159)

## Implements

- [`IPaymentLinkPreviewMetadata`](../interfaces/IPaymentLinkPreviewMetadata.md)

## Constructors

### new PaymentLinkPreviewMetadata()

> **new PaymentLinkPreviewMetadata**(`p`?): [`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:8160](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8160)

#### Parameters

##### p?

[`IPaymentLinkPreviewMetadata`](../interfaces/IPaymentLinkPreviewMetadata.md)

#### Returns

[`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

## Properties

### isBusinessVerified?

> `optional` **isBusinessVerified**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:8161](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8161)

#### Implementation of

[`IPaymentLinkPreviewMetadata`](../interfaces/IPaymentLinkPreviewMetadata.md).[`isBusinessVerified`](../interfaces/IPaymentLinkPreviewMetadata.md#isbusinessverified)

***

### providerName?

> `optional` **providerName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8162](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8162)

#### Implementation of

[`IPaymentLinkPreviewMetadata`](../interfaces/IPaymentLinkPreviewMetadata.md).[`providerName`](../interfaces/IPaymentLinkPreviewMetadata.md#providername)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8168](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8168)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:8163](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8163)

#### Parameters

##### properties?

[`IPaymentLinkPreviewMetadata`](../interfaces/IPaymentLinkPreviewMetadata.md)

#### Returns

[`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:8165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8165)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8164](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8164)

#### Parameters

##### m

[`IPaymentLinkPreviewMetadata`](../interfaces/IPaymentLinkPreviewMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

Defined in: [WAProto/index.d.ts:8166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8166)

#### Parameters

##### d

#### Returns

[`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8169](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8169)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8167)

#### Parameters

##### m

[`PaymentLinkPreviewMetadata`](PaymentLinkPreviewMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
