# Class: SyncDSnapshotFatalRecoveryResponse

Defined in: [WAProto/index.d.ts:8194](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8194)

## Implements

- [`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

## Constructors

### new SyncDSnapshotFatalRecoveryResponse()

> **new SyncDSnapshotFatalRecoveryResponse**(`p`?): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:8195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8195)

#### Parameters

##### p?

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

## Properties

### collectionSnapshot?

> `optional` **collectionSnapshot**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8196)

#### Implementation of

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md).[`collectionSnapshot`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md#collectionsnapshot)

***

### isCompressed?

> `optional` **isCompressed**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:8197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8197)

#### Implementation of

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md).[`isCompressed`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md#iscompressed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8203)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:8198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8198)

#### Parameters

##### properties?

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:8200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8200)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8199)

#### Parameters

##### m

[`ISyncDSnapshotFatalRecoveryResponse`](../interfaces/ISyncDSnapshotFatalRecoveryResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

Defined in: [WAProto/index.d.ts:8201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8201)

#### Parameters

##### d

#### Returns

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8204)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8202)

#### Parameters

##### m

[`SyncDSnapshotFatalRecoveryResponse`](SyncDSnapshotFatalRecoveryResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
