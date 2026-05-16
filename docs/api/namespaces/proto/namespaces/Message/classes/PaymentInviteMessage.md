# Class: PaymentInviteMessage

Defined in: [WAProto/index.d.ts:7641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7641)

## Implements

- [`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

## Constructors

### new PaymentInviteMessage()

> **new PaymentInviteMessage**(`p`?): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:7642](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7642)

#### Parameters

##### p?

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

## Properties

### expiryTimestamp?

> `optional` **expiryTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7644](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7644)

#### Implementation of

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md).[`expiryTimestamp`](../interfaces/IPaymentInviteMessage.md#expirytimestamp)

***

### serviceType?

> `optional` **serviceType**: `null` \| [`ServiceType`](../namespaces/PaymentInviteMessage/enumerations/ServiceType.md)

Defined in: [WAProto/index.d.ts:7643](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7643)

#### Implementation of

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md).[`serviceType`](../interfaces/IPaymentInviteMessage.md#servicetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7650](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7650)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:7645](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7645)

#### Parameters

##### properties?

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:7647](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7647)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7646](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7646)

#### Parameters

##### m

[`IPaymentInviteMessage`](../interfaces/IPaymentInviteMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentInviteMessage`](PaymentInviteMessage.md)

Defined in: [WAProto/index.d.ts:7648](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7648)

#### Parameters

##### d

#### Returns

[`PaymentInviteMessage`](PaymentInviteMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7651](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7651)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7649](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7649)

#### Parameters

##### m

[`PaymentInviteMessage`](PaymentInviteMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
