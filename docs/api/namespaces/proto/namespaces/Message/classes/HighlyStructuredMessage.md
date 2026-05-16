# Class: HighlyStructuredMessage

Defined in: [WAProto/index.d.ts:6409](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6409)

## Implements

- [`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md)

## Constructors

### new HighlyStructuredMessage()

> **new HighlyStructuredMessage**(`p`?): [`HighlyStructuredMessage`](HighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:6410](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6410)

#### Parameters

##### p?

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md)

#### Returns

[`HighlyStructuredMessage`](HighlyStructuredMessage.md)

## Properties

### deterministicLc?

> `optional` **deterministicLc**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6418)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`deterministicLc`](../interfaces/IHighlyStructuredMessage.md#deterministiclc)

***

### deterministicLg?

> `optional` **deterministicLg**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6417)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`deterministicLg`](../interfaces/IHighlyStructuredMessage.md#deterministiclg)

***

### elementName?

> `optional` **elementName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6412)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`elementName`](../interfaces/IHighlyStructuredMessage.md#elementname)

***

### fallbackLc?

> `optional` **fallbackLc**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6415)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`fallbackLc`](../interfaces/IHighlyStructuredMessage.md#fallbacklc)

***

### fallbackLg?

> `optional` **fallbackLg**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6414)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`fallbackLg`](../interfaces/IHighlyStructuredMessage.md#fallbacklg)

***

### hydratedHsm?

> `optional` **hydratedHsm**: `null` \| [`ITemplateMessage`](../interfaces/ITemplateMessage.md)

Defined in: [WAProto/index.d.ts:6419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6419)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`hydratedHsm`](../interfaces/IHighlyStructuredMessage.md#hydratedhsm)

***

### localizableParams

> **localizableParams**: [`IHSMLocalizableParameter`](../namespaces/HighlyStructuredMessage/interfaces/IHSMLocalizableParameter.md)[]

Defined in: [WAProto/index.d.ts:6416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6416)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`localizableParams`](../interfaces/IHighlyStructuredMessage.md#localizableparams)

***

### namespace?

> `optional` **namespace**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6411](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6411)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`namespace`](../interfaces/IHighlyStructuredMessage.md#namespace)

***

### params

> **params**: `string`[]

Defined in: [WAProto/index.d.ts:6413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6413)

#### Implementation of

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md).[`params`](../interfaces/IHighlyStructuredMessage.md#params)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6425](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6425)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HighlyStructuredMessage`](HighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:6420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6420)

#### Parameters

##### properties?

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md)

#### Returns

[`HighlyStructuredMessage`](HighlyStructuredMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HighlyStructuredMessage`](HighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:6422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6422)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HighlyStructuredMessage`](HighlyStructuredMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6421)

#### Parameters

##### m

[`IHighlyStructuredMessage`](../interfaces/IHighlyStructuredMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HighlyStructuredMessage`](HighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:6423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6423)

#### Parameters

##### d

#### Returns

[`HighlyStructuredMessage`](HighlyStructuredMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6426](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6426)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6424)

#### Parameters

##### m

[`HighlyStructuredMessage`](HighlyStructuredMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
