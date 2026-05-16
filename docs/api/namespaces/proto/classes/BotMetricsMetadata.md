# Class: BotMetricsMetadata

Defined in: [WAProto/index.d.ts:1626](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1626)

## Implements

- [`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

## Constructors

### new BotMetricsMetadata()

> **new BotMetricsMetadata**(`p`?): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:1627](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1627)

#### Parameters

##### p?

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

## Properties

### destinationEntryPoint?

> `optional` **destinationEntryPoint**: `null` \| [`BotMetricsEntryPoint`](../enumerations/BotMetricsEntryPoint.md)

Defined in: [WAProto/index.d.ts:1629](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1629)

#### Implementation of

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md).[`destinationEntryPoint`](../interfaces/IBotMetricsMetadata.md#destinationentrypoint)

***

### destinationId?

> `optional` **destinationId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1628](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1628)

#### Implementation of

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md).[`destinationId`](../interfaces/IBotMetricsMetadata.md#destinationid)

***

### threadOrigin?

> `optional` **threadOrigin**: `null` \| [`BotMetricsThreadEntryPoint`](../enumerations/BotMetricsThreadEntryPoint.md)

Defined in: [WAProto/index.d.ts:1630](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1630)

#### Implementation of

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md).[`threadOrigin`](../interfaces/IBotMetricsMetadata.md#threadorigin)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1636](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1636)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:1631](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1631)

#### Parameters

##### properties?

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:1633](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1633)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1632](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1632)

#### Parameters

##### m

[`IBotMetricsMetadata`](../interfaces/IBotMetricsMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMetricsMetadata`](BotMetricsMetadata.md)

Defined in: [WAProto/index.d.ts:1634](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1634)

#### Parameters

##### d

#### Returns

[`BotMetricsMetadata`](BotMetricsMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1637](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1637)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1635](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1635)

#### Parameters

##### m

[`BotMetricsMetadata`](BotMetricsMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
