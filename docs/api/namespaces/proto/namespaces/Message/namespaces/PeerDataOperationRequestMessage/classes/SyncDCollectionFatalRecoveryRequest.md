# Class: SyncDCollectionFatalRecoveryRequest

Defined in: [WAProto/index.d.ts:7925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7925)

## Implements

- [`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

## Constructors

### new SyncDCollectionFatalRecoveryRequest()

> **new SyncDCollectionFatalRecoveryRequest**(`p`?): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:7926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7926)

#### Parameters

##### p?

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

## Properties

### collectionName?

> `optional` **collectionName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7927)

#### Implementation of

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md).[`collectionName`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md#collectionname)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7928)

#### Implementation of

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md).[`timestamp`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7934)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:7929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7929)

#### Parameters

##### properties?

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:7931](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7931)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7930](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7930)

#### Parameters

##### m

[`ISyncDCollectionFatalRecoveryRequest`](../interfaces/ISyncDCollectionFatalRecoveryRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

Defined in: [WAProto/index.d.ts:7932](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7932)

#### Parameters

##### d

#### Returns

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7935)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7933)

#### Parameters

##### m

[`SyncDCollectionFatalRecoveryRequest`](SyncDCollectionFatalRecoveryRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
