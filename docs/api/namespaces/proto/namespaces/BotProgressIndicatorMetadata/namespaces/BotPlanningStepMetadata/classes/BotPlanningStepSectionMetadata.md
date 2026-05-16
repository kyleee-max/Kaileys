# Class: BotPlanningStepSectionMetadata

Defined in: [WAProto/index.d.ts:1869](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1869)

## Implements

- [`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

## Constructors

### new BotPlanningStepSectionMetadata()

> **new BotPlanningStepSectionMetadata**(`p`?): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:1870](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1870)

#### Parameters

##### p?

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

## Properties

### sectionBody?

> `optional` **sectionBody**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1872](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1872)

#### Implementation of

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md).[`sectionBody`](../interfaces/IBotPlanningStepSectionMetadata.md#sectionbody)

***

### sectionTitle?

> `optional` **sectionTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1871](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1871)

#### Implementation of

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md).[`sectionTitle`](../interfaces/IBotPlanningStepSectionMetadata.md#sectiontitle)

***

### sourcesMetadata

> **sourcesMetadata**: [`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)[]

Defined in: [WAProto/index.d.ts:1873](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1873)

#### Implementation of

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md).[`sourcesMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md#sourcesmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1879)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:1874](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1874)

#### Parameters

##### properties?

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:1876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1876)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1875)

#### Parameters

##### m

[`IBotPlanningStepSectionMetadata`](../interfaces/IBotPlanningStepSectionMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

Defined in: [WAProto/index.d.ts:1877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1877)

#### Parameters

##### d

#### Returns

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1880)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1878)

#### Parameters

##### m

[`BotPlanningStepSectionMetadata`](BotPlanningStepSectionMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
