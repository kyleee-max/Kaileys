# Class: BotUnifiedResponseMutation

Defined in: [WAProto/index.d.ts:2245](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2245)

## Implements

- [`IBotUnifiedResponseMutation`](../interfaces/IBotUnifiedResponseMutation.md)

## Constructors

### new BotUnifiedResponseMutation()

> **new BotUnifiedResponseMutation**(`p`?): [`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

Defined in: [WAProto/index.d.ts:2246](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2246)

#### Parameters

##### p?

[`IBotUnifiedResponseMutation`](../interfaces/IBotUnifiedResponseMutation.md)

#### Returns

[`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

## Properties

### mediaDetailsMetadataList

> **mediaDetailsMetadataList**: [`IMediaDetailsMetadata`](../namespaces/BotUnifiedResponseMutation/interfaces/IMediaDetailsMetadata.md)[]

Defined in: [WAProto/index.d.ts:2248](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2248)

#### Implementation of

[`IBotUnifiedResponseMutation`](../interfaces/IBotUnifiedResponseMutation.md).[`mediaDetailsMetadataList`](../interfaces/IBotUnifiedResponseMutation.md#mediadetailsmetadatalist)

***

### sbsMetadata?

> `optional` **sbsMetadata**: `null` \| [`ISideBySideMetadata`](../namespaces/BotUnifiedResponseMutation/interfaces/ISideBySideMetadata.md)

Defined in: [WAProto/index.d.ts:2247](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2247)

#### Implementation of

[`IBotUnifiedResponseMutation`](../interfaces/IBotUnifiedResponseMutation.md).[`sbsMetadata`](../interfaces/IBotUnifiedResponseMutation.md#sbsmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2254](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2254)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

Defined in: [WAProto/index.d.ts:2249](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2249)

#### Parameters

##### properties?

[`IBotUnifiedResponseMutation`](../interfaces/IBotUnifiedResponseMutation.md)

#### Returns

[`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

Defined in: [WAProto/index.d.ts:2251](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2251)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2250](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2250)

#### Parameters

##### m

[`IBotUnifiedResponseMutation`](../interfaces/IBotUnifiedResponseMutation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

Defined in: [WAProto/index.d.ts:2252](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2252)

#### Parameters

##### d

#### Returns

[`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2255](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2255)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2253](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2253)

#### Parameters

##### m

[`BotUnifiedResponseMutation`](BotUnifiedResponseMutation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
