# Class: BotPlanningStepMetadata

Defined in: [WAProto/index.d.ts:1791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1791)

## Implements

- [`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

## Constructors

### new BotPlanningStepMetadata()

> **new BotPlanningStepMetadata**(`p`?): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:1792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1792)

#### Parameters

##### p?

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

## Properties

### isEnhancedSearch?

> `optional` **isEnhancedSearch**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:1798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1798)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`isEnhancedSearch`](../interfaces/IBotPlanningStepMetadata.md#isenhancedsearch)

***

### isReasoning?

> `optional` **isReasoning**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:1797](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1797)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`isReasoning`](../interfaces/IBotPlanningStepMetadata.md#isreasoning)

***

### sections

> **sections**: [`IBotPlanningStepSectionMetadata`](../namespaces/BotPlanningStepMetadata/interfaces/IBotPlanningStepSectionMetadata.md)[]

Defined in: [WAProto/index.d.ts:1799](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1799)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`sections`](../interfaces/IBotPlanningStepMetadata.md#sections)

***

### sourcesMetadata

> **sourcesMetadata**: [`IBotPlanningSearchSourcesMetadata`](../namespaces/BotPlanningStepMetadata/interfaces/IBotPlanningSearchSourcesMetadata.md)[]

Defined in: [WAProto/index.d.ts:1795](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1795)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`sourcesMetadata`](../interfaces/IBotPlanningStepMetadata.md#sourcesmetadata)

***

### status?

> `optional` **status**: `null` \| [`PlanningStepStatus`](../namespaces/BotPlanningStepMetadata/enumerations/PlanningStepStatus.md)

Defined in: [WAProto/index.d.ts:1796](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1796)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`status`](../interfaces/IBotPlanningStepMetadata.md#status)

***

### statusBody?

> `optional` **statusBody**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1794](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1794)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`statusBody`](../interfaces/IBotPlanningStepMetadata.md#statusbody)

***

### statusTitle?

> `optional` **statusTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1793)

#### Implementation of

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md).[`statusTitle`](../interfaces/IBotPlanningStepMetadata.md#statustitle)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1805](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1805)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:1800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1800)

#### Parameters

##### properties?

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:1802](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1802)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1801)

#### Parameters

##### m

[`IBotPlanningStepMetadata`](../interfaces/IBotPlanningStepMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

Defined in: [WAProto/index.d.ts:1803](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1803)

#### Parameters

##### d

#### Returns

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1806)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1804](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1804)

#### Parameters

##### m

[`BotPlanningStepMetadata`](BotPlanningStepMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
