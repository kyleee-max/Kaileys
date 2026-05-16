# Class: MerchantPaymentPartnerAction

Defined in: [WAProto/index.d.ts:12301](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12301)

## Implements

- [`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

## Constructors

### new MerchantPaymentPartnerAction()

> **new MerchantPaymentPartnerAction**(`p`?): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:12302](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12302)

#### Parameters

##### p?

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

## Properties

### country

> **country**: `string`

Defined in: [WAProto/index.d.ts:12304](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12304)

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`country`](../interfaces/IMerchantPaymentPartnerAction.md#country)

***

### credentialId?

> `optional` **credentialId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12306](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12306)

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`credentialId`](../interfaces/IMerchantPaymentPartnerAction.md#credentialid)

***

### gatewayName?

> `optional` **gatewayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12305](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12305)

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`gatewayName`](../interfaces/IMerchantPaymentPartnerAction.md#gatewayname)

***

### status

> **status**: [`Status`](../namespaces/MerchantPaymentPartnerAction/enumerations/Status.md)

Defined in: [WAProto/index.d.ts:12303](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12303)

#### Implementation of

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md).[`status`](../interfaces/IMerchantPaymentPartnerAction.md#status)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12312](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12312)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:12307](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12307)

#### Parameters

##### properties?

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:12309](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12309)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12308](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12308)

#### Parameters

##### m

[`IMerchantPaymentPartnerAction`](../interfaces/IMerchantPaymentPartnerAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

Defined in: [WAProto/index.d.ts:12310](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12310)

#### Parameters

##### d

#### Returns

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12313](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12313)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12311](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12311)

#### Parameters

##### m

[`MerchantPaymentPartnerAction`](MerchantPaymentPartnerAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
