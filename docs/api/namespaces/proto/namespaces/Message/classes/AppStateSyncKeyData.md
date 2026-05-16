# Class: AppStateSyncKeyData

Defined in: [WAProto/index.d.ts:5453](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5453)

## Implements

- [`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

## Constructors

### new AppStateSyncKeyData()

> **new AppStateSyncKeyData**(`p`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:5454](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5454)

#### Parameters

##### p?

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

## Properties

### fingerprint?

> `optional` **fingerprint**: `null` \| [`IAppStateSyncKeyFingerprint`](../interfaces/IAppStateSyncKeyFingerprint.md)

Defined in: [WAProto/index.d.ts:5456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5456)

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`fingerprint`](../interfaces/IAppStateSyncKeyData.md#fingerprint)

***

### keyData?

> `optional` **keyData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5455](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5455)

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`keyData`](../interfaces/IAppStateSyncKeyData.md#keydata)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5457)

#### Implementation of

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md).[`timestamp`](../interfaces/IAppStateSyncKeyData.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5463)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:5458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5458)

#### Parameters

##### properties?

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:5460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5460)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5459)

#### Parameters

##### m

[`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateSyncKeyData`](AppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:5461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5461)

#### Parameters

##### d

#### Returns

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5464)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5462)

#### Parameters

##### m

[`AppStateSyncKeyData`](AppStateSyncKeyData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
