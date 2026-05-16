# Class: BotQuotaMetadata

Defined in: [WAProto/index.d.ts:1964](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1964)

## Implements

- [`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

## Constructors

### new BotQuotaMetadata()

> **new BotQuotaMetadata**(`p`?): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1965](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1965)

#### Parameters

##### p?

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

## Properties

### botFeatureQuotaMetadata

> **botFeatureQuotaMetadata**: [`IBotFeatureQuotaMetadata`](../namespaces/BotQuotaMetadata/interfaces/IBotFeatureQuotaMetadata.md)[]

Defined in: [WAProto/index.d.ts:1966](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1966)

#### Implementation of

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md).[`botFeatureQuotaMetadata`](../interfaces/IBotQuotaMetadata.md#botfeaturequotametadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1972)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1967](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1967)

#### Parameters

##### properties?

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1969)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1968)

#### Parameters

##### m

[`IBotQuotaMetadata`](../interfaces/IBotQuotaMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotQuotaMetadata`](BotQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1970)

#### Parameters

##### d

#### Returns

[`BotQuotaMetadata`](BotQuotaMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1973)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1971)

#### Parameters

##### m

[`BotQuotaMetadata`](BotQuotaMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
