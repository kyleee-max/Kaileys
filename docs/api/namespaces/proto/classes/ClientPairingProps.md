# Class: ClientPairingProps

Defined in: [WAProto/index.d.ts:2618](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2618)

## Implements

- [`IClientPairingProps`](../interfaces/IClientPairingProps.md)

## Constructors

### new ClientPairingProps()

> **new ClientPairingProps**(`p`?): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:2619](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2619)

#### Parameters

##### p?

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

## Properties

### isChatDbLidMigrated?

> `optional` **isChatDbLidMigrated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2620](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2620)

#### Implementation of

[`IClientPairingProps`](../interfaces/IClientPairingProps.md).[`isChatDbLidMigrated`](../interfaces/IClientPairingProps.md#ischatdblidmigrated)

***

### isSyncdPureLidSession?

> `optional` **isSyncdPureLidSession**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2621](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2621)

#### Implementation of

[`IClientPairingProps`](../interfaces/IClientPairingProps.md).[`isSyncdPureLidSession`](../interfaces/IClientPairingProps.md#issyncdpurelidsession)

***

### isSyncdSnapshotRecoveryEnabled?

> `optional` **isSyncdSnapshotRecoveryEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2622](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2622)

#### Implementation of

[`IClientPairingProps`](../interfaces/IClientPairingProps.md).[`isSyncdSnapshotRecoveryEnabled`](../interfaces/IClientPairingProps.md#issyncdsnapshotrecoveryenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2628](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2628)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:2623](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2623)

#### Parameters

##### properties?

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:2625](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2625)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2624](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2624)

#### Parameters

##### m

[`IClientPairingProps`](../interfaces/IClientPairingProps.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ClientPairingProps`](ClientPairingProps.md)

Defined in: [WAProto/index.d.ts:2626](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2626)

#### Parameters

##### d

#### Returns

[`ClientPairingProps`](ClientPairingProps.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2629](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2629)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2627](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2627)

#### Parameters

##### m

[`ClientPairingProps`](ClientPairingProps.md)

##### o?

`IConversionOptions`

#### Returns

`object`
