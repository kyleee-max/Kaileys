# Class: AppStateSyncKeyFingerprint

Defined in: [WAProto/index.d.ts:5473](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5473)

## Implements

- [`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

## Constructors

### new AppStateSyncKeyFingerprint()

> **new AppStateSyncKeyFingerprint**(`p`?): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:5474](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5474)

#### Parameters

##### p?

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

## Properties

### currentIndex?

> `optional` **currentIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5476](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5476)

#### Implementation of

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md).[`currentIndex`](../interfaces/IAppStateSyncKeyFingerprint.md#currentindex)

***

### deviceIndexes

> **deviceIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:5477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5477)

#### Implementation of

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md).[`deviceIndexes`](../interfaces/IAppStateSyncKeyFingerprint.md#deviceindexes)

***

### rawId?

> `optional` **rawId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5475](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5475)

#### Implementation of

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md).[`rawId`](../interfaces/IAppStateSyncKeyFingerprint.md#rawid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5483)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:5478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5478)

#### Parameters

##### properties?

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:5480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5480)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5479)

#### Parameters

##### m

[`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:5481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5481)

#### Parameters

##### d

#### Returns

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5484)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5482)

#### Parameters

##### m

[`AppStateSyncKeyFingerprint`](AppStateSyncKeyFingerprint.md)

##### o?

`IConversionOptions`

#### Returns

`object`
