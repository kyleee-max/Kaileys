# Class: BotPlanningSearchSourceMetadata

Defined in: [WAProto/index.d.ts:1818](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1818)

## Implements

- [`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

## Constructors

### new BotPlanningSearchSourceMetadata()

> **new BotPlanningSearchSourceMetadata**(`p`?): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:1819](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1819)

#### Parameters

##### p?

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

## Properties

### favIconUrl?

> `optional` **favIconUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1823](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1823)

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`favIconUrl`](../interfaces/IBotPlanningSearchSourceMetadata.md#faviconurl)

***

### provider?

> `optional` **provider**: `null` \| [`BotSearchSourceProvider`](../enumerations/BotSearchSourceProvider.md)

Defined in: [WAProto/index.d.ts:1821](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1821)

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`provider`](../interfaces/IBotPlanningSearchSourceMetadata.md#provider)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1822](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1822)

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`sourceUrl`](../interfaces/IBotPlanningSearchSourceMetadata.md#sourceurl)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1820](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1820)

#### Implementation of

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md).[`title`](../interfaces/IBotPlanningSearchSourceMetadata.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1829)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:1824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1824)

#### Parameters

##### properties?

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:1826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1826)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1825)

#### Parameters

##### m

[`IBotPlanningSearchSourceMetadata`](../interfaces/IBotPlanningSearchSourceMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

Defined in: [WAProto/index.d.ts:1827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1827)

#### Parameters

##### d

#### Returns

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1830)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1828)

#### Parameters

##### m

[`BotPlanningSearchSourceMetadata`](BotPlanningSearchSourceMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
