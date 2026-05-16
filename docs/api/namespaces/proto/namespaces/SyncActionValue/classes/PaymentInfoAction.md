# Class: PaymentInfoAction

Defined in: [WAProto/index.d.ts:12456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12456)

## Implements

- [`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

## Constructors

### new PaymentInfoAction()

> **new PaymentInfoAction**(`p`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:12457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12457)

#### Parameters

##### p?

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

## Properties

### cpi?

> `optional` **cpi**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12458)

#### Implementation of

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md).[`cpi`](../interfaces/IPaymentInfoAction.md#cpi)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12464)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:12459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12459)

#### Parameters

##### properties?

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:12461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12461)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12460)

#### Parameters

##### m

[`IPaymentInfoAction`](../interfaces/IPaymentInfoAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PaymentInfoAction`](PaymentInfoAction.md)

Defined in: [WAProto/index.d.ts:12462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12462)

#### Parameters

##### d

#### Returns

[`PaymentInfoAction`](PaymentInfoAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12465)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12463)

#### Parameters

##### m

[`PaymentInfoAction`](PaymentInfoAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
