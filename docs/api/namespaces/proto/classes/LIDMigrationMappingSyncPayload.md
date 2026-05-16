# Class: LIDMigrationMappingSyncPayload

Defined in: [WAProto/index.d.ts:4990](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4990)

## Implements

- [`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

## Constructors

### new LIDMigrationMappingSyncPayload()

> **new LIDMigrationMappingSyncPayload**(`p`?): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:4991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4991)

#### Parameters

##### p?

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

## Properties

### chatDbMigrationTimestamp?

> `optional` **chatDbMigrationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4993](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4993)

#### Implementation of

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md).[`chatDbMigrationTimestamp`](../interfaces/ILIDMigrationMappingSyncPayload.md#chatdbmigrationtimestamp)

***

### pnToLidMappings

> **pnToLidMappings**: [`ILIDMigrationMapping`](../interfaces/ILIDMigrationMapping.md)[]

Defined in: [WAProto/index.d.ts:4992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4992)

#### Implementation of

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md).[`pnToLidMappings`](../interfaces/ILIDMigrationMappingSyncPayload.md#pntolidmappings)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4999](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4999)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:4994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4994)

#### Parameters

##### properties?

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:4996](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4996)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4995)

#### Parameters

##### m

[`ILIDMigrationMappingSyncPayload`](../interfaces/ILIDMigrationMappingSyncPayload.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

Defined in: [WAProto/index.d.ts:4997](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4997)

#### Parameters

##### d

#### Returns

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5000](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5000)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4998](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4998)

#### Parameters

##### m

[`LIDMigrationMappingSyncPayload`](LIDMigrationMappingSyncPayload.md)

##### o?

`IConversionOptions`

#### Returns

`object`
