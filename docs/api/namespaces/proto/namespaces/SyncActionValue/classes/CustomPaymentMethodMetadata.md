# Class: CustomPaymentMethodMetadata

Defined in: [WAProto/index.d.ts:11881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11881)

## Implements

- [`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

## Constructors

### new CustomPaymentMethodMetadata()

> **new CustomPaymentMethodMetadata**(`p`?): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:11882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11882)

#### Parameters

##### p?

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

## Properties

### key

> **key**: `string`

Defined in: [WAProto/index.d.ts:11883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11883)

#### Implementation of

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md).[`key`](../interfaces/ICustomPaymentMethodMetadata.md#key)

***

### value

> **value**: `string`

Defined in: [WAProto/index.d.ts:11884](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11884)

#### Implementation of

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md).[`value`](../interfaces/ICustomPaymentMethodMetadata.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11890](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11890)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:11885](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11885)

#### Parameters

##### properties?

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:11887](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11887)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11886](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11886)

#### Parameters

##### m

[`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

Defined in: [WAProto/index.d.ts:11888](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11888)

#### Parameters

##### d

#### Returns

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11891](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11891)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11889](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11889)

#### Parameters

##### m

[`CustomPaymentMethodMetadata`](CustomPaymentMethodMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
