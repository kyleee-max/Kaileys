# Class: HSMCurrency

Defined in: [WAProto/index.d.ts:6459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6459)

## Implements

- [`IHSMCurrency`](../interfaces/IHSMCurrency.md)

## Constructors

### new HSMCurrency()

> **new HSMCurrency**(`p`?): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:6460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6460)

#### Parameters

##### p?

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

#### Returns

[`HSMCurrency`](HSMCurrency.md)

## Properties

### amount1000?

> `optional` **amount1000**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6462)

#### Implementation of

[`IHSMCurrency`](../interfaces/IHSMCurrency.md).[`amount1000`](../interfaces/IHSMCurrency.md#amount1000)

***

### currencyCode?

> `optional` **currencyCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6461)

#### Implementation of

[`IHSMCurrency`](../interfaces/IHSMCurrency.md).[`currencyCode`](../interfaces/IHSMCurrency.md#currencycode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6468](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6468)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:6463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6463)

#### Parameters

##### properties?

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

#### Returns

[`HSMCurrency`](HSMCurrency.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:6465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6465)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HSMCurrency`](HSMCurrency.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6464)

#### Parameters

##### m

[`IHSMCurrency`](../interfaces/IHSMCurrency.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HSMCurrency`](HSMCurrency.md)

Defined in: [WAProto/index.d.ts:6466](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6466)

#### Parameters

##### d

#### Returns

[`HSMCurrency`](HSMCurrency.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6469](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6469)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6467](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6467)

#### Parameters

##### m

[`HSMCurrency`](HSMCurrency.md)

##### o?

`IConversionOptions`

#### Returns

`object`
