# Class: CustomPaymentMethodsAction

Defined in: [WAProto/index.d.ts:11898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11898)

## Implements

- [`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

## Constructors

### new CustomPaymentMethodsAction()

> **new CustomPaymentMethodsAction**(`p`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:11899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11899)

#### Parameters

##### p?

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

## Properties

### customPaymentMethods

> **customPaymentMethods**: [`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)[]

Defined in: [WAProto/index.d.ts:11900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11900)

#### Implementation of

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md).[`customPaymentMethods`](../interfaces/ICustomPaymentMethodsAction.md#custompaymentmethods)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11906](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11906)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:11901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11901)

#### Parameters

##### properties?

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:11903](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11903)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11902](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11902)

#### Parameters

##### m

[`ICustomPaymentMethodsAction`](../interfaces/ICustomPaymentMethodsAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

Defined in: [WAProto/index.d.ts:11904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11904)

#### Parameters

##### d

#### Returns

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11907)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11905)

#### Parameters

##### m

[`CustomPaymentMethodsAction`](CustomPaymentMethodsAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
