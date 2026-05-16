# Class: LIDMigrationMappingSyncMessage

Defined in: [WAProto/index.d.ts:4973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4973)

## Implements

- [`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

## Constructors

### new LIDMigrationMappingSyncMessage()

> **new LIDMigrationMappingSyncMessage**(`p`?): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:4974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4974)

#### Parameters

##### p?

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

## Properties

### encodedMappingPayload?

> `optional` **encodedMappingPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4975](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4975)

#### Implementation of

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md).[`encodedMappingPayload`](../interfaces/ILIDMigrationMappingSyncMessage.md#encodedmappingpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4981](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4981)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:4976](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4976)

#### Parameters

##### properties?

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:4978](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4978)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4977](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4977)

#### Parameters

##### m

[`ILIDMigrationMappingSyncMessage`](../interfaces/ILIDMigrationMappingSyncMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:4979](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4979)

#### Parameters

##### d

#### Returns

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4982](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4982)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4980](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4980)

#### Parameters

##### m

[`LIDMigrationMappingSyncMessage`](LIDMigrationMappingSyncMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
