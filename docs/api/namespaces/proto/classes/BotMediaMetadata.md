# Class: BotMediaMetadata

Defined in: [WAProto/index.d.ts:1358](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1358)

## Implements

- [`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

## Constructors

### new BotMediaMetadata()

> **new BotMediaMetadata**(`p`?): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:1359](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1359)

#### Parameters

##### p?

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1363](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1363)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`directPath`](../interfaces/IBotMediaMetadata.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1362](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1362)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`fileEncSha256`](../interfaces/IBotMediaMetadata.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1360](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1360)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`fileSha256`](../interfaces/IBotMediaMetadata.md#filesha256)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1361](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1361)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`mediaKey`](../interfaces/IBotMediaMetadata.md#mediakey)

***

### mediaKeyTimestamp?

> `optional` **mediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:1364](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1364)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`mediaKeyTimestamp`](../interfaces/IBotMediaMetadata.md#mediakeytimestamp)

***

### mimetype?

> `optional` **mimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:1365](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1365)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`mimetype`](../interfaces/IBotMediaMetadata.md#mimetype)

***

### orientationType?

> `optional` **orientationType**: `null` \| [`OrientationType`](../namespaces/BotMediaMetadata/enumerations/OrientationType.md)

Defined in: [WAProto/index.d.ts:1366](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1366)

#### Implementation of

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md).[`orientationType`](../interfaces/IBotMediaMetadata.md#orientationtype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1372)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:1367](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1367)

#### Parameters

##### properties?

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:1369](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1369)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1368](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1368)

#### Parameters

##### m

[`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMediaMetadata`](BotMediaMetadata.md)

Defined in: [WAProto/index.d.ts:1370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1370)

#### Parameters

##### d

#### Returns

[`BotMediaMetadata`](BotMediaMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1373)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1371)

#### Parameters

##### m

[`BotMediaMetadata`](BotMediaMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
