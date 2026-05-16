# Class: CustomPaymentMethod

Defined in: [WAProto/index.d.ts:11861](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11861)

## Implements

- [`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

## Constructors

### new CustomPaymentMethod()

> **new CustomPaymentMethod**(`p`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:11862](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11862)

#### Parameters

##### p?

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

## Properties

### country

> **country**: `string`

Defined in: [WAProto/index.d.ts:11864](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11864)

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`country`](../interfaces/ICustomPaymentMethod.md#country)

***

### credentialId

> **credentialId**: `string`

Defined in: [WAProto/index.d.ts:11863](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11863)

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`credentialId`](../interfaces/ICustomPaymentMethod.md#credentialid)

***

### metadata

> **metadata**: [`ICustomPaymentMethodMetadata`](../interfaces/ICustomPaymentMethodMetadata.md)[]

Defined in: [WAProto/index.d.ts:11866](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11866)

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`metadata`](../interfaces/ICustomPaymentMethod.md#metadata)

***

### type

> **type**: `string`

Defined in: [WAProto/index.d.ts:11865](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11865)

#### Implementation of

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md).[`type`](../interfaces/ICustomPaymentMethod.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11872](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11872)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:11867](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11867)

#### Parameters

##### properties?

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:11869](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11869)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11868](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11868)

#### Parameters

##### m

[`ICustomPaymentMethod`](../interfaces/ICustomPaymentMethod.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CustomPaymentMethod`](CustomPaymentMethod.md)

Defined in: [WAProto/index.d.ts:11870](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11870)

#### Parameters

##### d

#### Returns

[`CustomPaymentMethod`](CustomPaymentMethod.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11873](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11873)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11871](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11871)

#### Parameters

##### m

[`CustomPaymentMethod`](CustomPaymentMethod.md)

##### o?

`IConversionOptions`

#### Returns

`object`
