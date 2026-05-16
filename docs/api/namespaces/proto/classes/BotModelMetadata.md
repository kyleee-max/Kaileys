# Class: BotModelMetadata

Defined in: [WAProto/index.d.ts:1678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1678)

## Implements

- [`IBotModelMetadata`](../interfaces/IBotModelMetadata.md)

## Constructors

### new BotModelMetadata()

> **new BotModelMetadata**(`p`?): [`BotModelMetadata`](BotModelMetadata.md)

Defined in: [WAProto/index.d.ts:1679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1679)

#### Parameters

##### p?

[`IBotModelMetadata`](../interfaces/IBotModelMetadata.md)

#### Returns

[`BotModelMetadata`](BotModelMetadata.md)

## Properties

### modelNameOverride?

> `optional` **modelNameOverride**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1682)

#### Implementation of

[`IBotModelMetadata`](../interfaces/IBotModelMetadata.md).[`modelNameOverride`](../interfaces/IBotModelMetadata.md#modelnameoverride)

***

### modelType?

> `optional` **modelType**: `null` \| [`ModelType`](../namespaces/BotModelMetadata/enumerations/ModelType.md)

Defined in: [WAProto/index.d.ts:1680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1680)

#### Implementation of

[`IBotModelMetadata`](../interfaces/IBotModelMetadata.md).[`modelType`](../interfaces/IBotModelMetadata.md#modeltype)

***

### premiumModelStatus?

> `optional` **premiumModelStatus**: `null` \| [`PremiumModelStatus`](../namespaces/BotModelMetadata/enumerations/PremiumModelStatus.md)

Defined in: [WAProto/index.d.ts:1681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1681)

#### Implementation of

[`IBotModelMetadata`](../interfaces/IBotModelMetadata.md).[`premiumModelStatus`](../interfaces/IBotModelMetadata.md#premiummodelstatus)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1688](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1688)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotModelMetadata`](BotModelMetadata.md)

Defined in: [WAProto/index.d.ts:1683](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1683)

#### Parameters

##### properties?

[`IBotModelMetadata`](../interfaces/IBotModelMetadata.md)

#### Returns

[`BotModelMetadata`](BotModelMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotModelMetadata`](BotModelMetadata.md)

Defined in: [WAProto/index.d.ts:1685](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1685)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotModelMetadata`](BotModelMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1684](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1684)

#### Parameters

##### m

[`IBotModelMetadata`](../interfaces/IBotModelMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotModelMetadata`](BotModelMetadata.md)

Defined in: [WAProto/index.d.ts:1686](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1686)

#### Parameters

##### d

#### Returns

[`BotModelMetadata`](BotModelMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1689](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1689)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1687](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1687)

#### Parameters

##### m

[`BotModelMetadata`](BotModelMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
