# Class: BotProgressIndicatorMetadata

Defined in: [WAProto/index.d.ts:1766](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1766)

## Implements

- [`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

## Constructors

### new BotProgressIndicatorMetadata()

> **new BotProgressIndicatorMetadata**(`p`?): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:1767](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1767)

#### Parameters

##### p?

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

## Properties

### progressDescription?

> `optional` **progressDescription**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1768](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1768)

#### Implementation of

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md).[`progressDescription`](../interfaces/IBotProgressIndicatorMetadata.md#progressdescription)

***

### stepsMetadata

> **stepsMetadata**: [`IBotPlanningStepMetadata`](../namespaces/BotProgressIndicatorMetadata/interfaces/IBotPlanningStepMetadata.md)[]

Defined in: [WAProto/index.d.ts:1769](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1769)

#### Implementation of

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md).[`stepsMetadata`](../interfaces/IBotProgressIndicatorMetadata.md#stepsmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1775)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:1770](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1770)

#### Parameters

##### properties?

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:1772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1772)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1771)

#### Parameters

##### m

[`IBotProgressIndicatorMetadata`](../interfaces/IBotProgressIndicatorMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

Defined in: [WAProto/index.d.ts:1773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1773)

#### Parameters

##### d

#### Returns

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1776)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1774)

#### Parameters

##### m

[`BotProgressIndicatorMetadata`](BotProgressIndicatorMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
