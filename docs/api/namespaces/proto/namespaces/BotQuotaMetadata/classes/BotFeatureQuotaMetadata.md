# Class: BotFeatureQuotaMetadata

Defined in: [WAProto/index.d.ts:1984](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1984)

## Implements

- [`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

## Constructors

### new BotFeatureQuotaMetadata()

> **new BotFeatureQuotaMetadata**(`p`?): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1985](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1985)

#### Parameters

##### p?

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

## Properties

### expirationTimestamp?

> `optional` **expirationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:1988](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1988)

#### Implementation of

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md).[`expirationTimestamp`](../interfaces/IBotFeatureQuotaMetadata.md#expirationtimestamp)

***

### featureType?

> `optional` **featureType**: `null` \| [`BotFeatureType`](../namespaces/BotFeatureQuotaMetadata/enumerations/BotFeatureType.md)

Defined in: [WAProto/index.d.ts:1986](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1986)

#### Implementation of

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md).[`featureType`](../interfaces/IBotFeatureQuotaMetadata.md#featuretype)

***

### remainingQuota?

> `optional` **remainingQuota**: `null` \| `number`

Defined in: [WAProto/index.d.ts:1987](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1987)

#### Implementation of

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md).[`remainingQuota`](../interfaces/IBotFeatureQuotaMetadata.md#remainingquota)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1994)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1989](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1989)

#### Parameters

##### properties?

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1991)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1990](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1990)

#### Parameters

##### m

[`IBotFeatureQuotaMetadata`](../interfaces/IBotFeatureQuotaMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

Defined in: [WAProto/index.d.ts:1992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1992)

#### Parameters

##### d

#### Returns

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1995)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1993](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1993)

#### Parameters

##### m

[`BotFeatureQuotaMetadata`](BotFeatureQuotaMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
