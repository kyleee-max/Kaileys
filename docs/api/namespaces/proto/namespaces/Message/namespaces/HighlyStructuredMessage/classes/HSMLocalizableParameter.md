# Class: HSMLocalizableParameter

Defined in: [WAProto/index.d.ts:6437](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6437)

## Implements

- [`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

## Constructors

### new HSMLocalizableParameter()

> **new HSMLocalizableParameter**(`p`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:6438](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6438)

#### Parameters

##### p?

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

## Properties

### currency?

> `optional` **currency**: `null` \| [`IHSMCurrency`](../namespaces/HSMLocalizableParameter/interfaces/IHSMCurrency.md)

Defined in: [WAProto/index.d.ts:6440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6440)

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`currency`](../interfaces/IHSMLocalizableParameter.md#currency)

***

### dateTime?

> `optional` **dateTime**: `null` \| [`IHSMDateTime`](../namespaces/HSMLocalizableParameter/interfaces/IHSMDateTime.md)

Defined in: [WAProto/index.d.ts:6441](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6441)

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`dateTime`](../interfaces/IHSMLocalizableParameter.md#datetime)

***

### default?

> `optional` **default**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6439)

#### Implementation of

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md).[`default`](../interfaces/IHSMLocalizableParameter.md#default)

***

### paramOneof?

> `optional` **paramOneof**: `"currency"` \| `"dateTime"`

Defined in: [WAProto/index.d.ts:6442](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6442)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6448](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6448)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:6443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6443)

#### Parameters

##### properties?

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:6445](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6445)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6444)

#### Parameters

##### m

[`IHSMLocalizableParameter`](../interfaces/IHSMLocalizableParameter.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HSMLocalizableParameter`](HSMLocalizableParameter.md)

Defined in: [WAProto/index.d.ts:6446](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6446)

#### Parameters

##### d

#### Returns

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6449](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6449)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6447](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6447)

#### Parameters

##### m

[`HSMLocalizableParameter`](HSMLocalizableParameter.md)

##### o?

`IConversionOptions`

#### Returns

`object`
