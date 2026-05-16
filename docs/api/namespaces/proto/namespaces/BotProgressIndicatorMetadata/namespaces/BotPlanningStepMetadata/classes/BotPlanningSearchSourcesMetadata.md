# Class: BotPlanningSearchSourcesMetadata

Defined in: [WAProto/index.d.ts:1839](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1839)

## Implements

- [`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

## Constructors

### new BotPlanningSearchSourcesMetadata()

> **new BotPlanningSearchSourcesMetadata**(`p`?): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:1840](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1840)

#### Parameters

##### p?

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

## Properties

### provider?

> `optional` **provider**: `null` \| [`BotPlanningSearchSourceProvider`](../namespaces/BotPlanningSearchSourcesMetadata/enumerations/BotPlanningSearchSourceProvider.md)

Defined in: [WAProto/index.d.ts:1842](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1842)

#### Implementation of

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md).[`provider`](../interfaces/IBotPlanningSearchSourcesMetadata.md#provider)

***

### sourceTitle?

> `optional` **sourceTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1841](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1841)

#### Implementation of

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md).[`sourceTitle`](../interfaces/IBotPlanningSearchSourcesMetadata.md#sourcetitle)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1843](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1843)

#### Implementation of

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md).[`sourceUrl`](../interfaces/IBotPlanningSearchSourcesMetadata.md#sourceurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1849](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1849)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:1844](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1844)

#### Parameters

##### properties?

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:1846](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1846)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1845](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1845)

#### Parameters

##### m

[`IBotPlanningSearchSourcesMetadata`](../interfaces/IBotPlanningSearchSourcesMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:1847](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1847)

#### Parameters

##### d

#### Returns

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1850](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1850)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1848](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1848)

#### Parameters

##### m

[`BotPlanningSearchSourcesMetadata`](BotPlanningSearchSourcesMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
