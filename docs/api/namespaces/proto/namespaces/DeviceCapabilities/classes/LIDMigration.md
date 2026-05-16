# Class: LIDMigration

Defined in: [WAProto/index.d.ts:3784](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3784)

## Implements

- [`ILIDMigration`](../interfaces/ILIDMigration.md)

## Constructors

### new LIDMigration()

> **new LIDMigration**(`p`?): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:3785](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3785)

#### Parameters

##### p?

[`ILIDMigration`](../interfaces/ILIDMigration.md)

#### Returns

[`LIDMigration`](LIDMigration.md)

## Properties

### chatDbMigrationTimestamp?

> `optional` **chatDbMigrationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3786](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3786)

#### Implementation of

[`ILIDMigration`](../interfaces/ILIDMigration.md).[`chatDbMigrationTimestamp`](../interfaces/ILIDMigration.md#chatdbmigrationtimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3792)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:3787](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3787)

#### Parameters

##### properties?

[`ILIDMigration`](../interfaces/ILIDMigration.md)

#### Returns

[`LIDMigration`](LIDMigration.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:3789](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3789)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LIDMigration`](LIDMigration.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3788](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3788)

#### Parameters

##### m

[`ILIDMigration`](../interfaces/ILIDMigration.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LIDMigration`](LIDMigration.md)

Defined in: [WAProto/index.d.ts:3790](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3790)

#### Parameters

##### d

#### Returns

[`LIDMigration`](LIDMigration.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3793)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3791)

#### Parameters

##### m

[`LIDMigration`](LIDMigration.md)

##### o?

`IConversionOptions`

#### Returns

`object`
