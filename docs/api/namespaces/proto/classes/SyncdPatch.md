# Class: SyncdPatch

Defined in: [WAProto/index.d.ts:13060](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13060)

## Implements

- [`ISyncdPatch`](../interfaces/ISyncdPatch.md)

## Constructors

### new SyncdPatch()

> **new SyncdPatch**(`p`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:13061](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13061)

#### Parameters

##### p?

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

#### Returns

[`SyncdPatch`](SyncdPatch.md)

## Properties

### clientDebugData?

> `optional` **clientDebugData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13070)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`clientDebugData`](../interfaces/ISyncdPatch.md#clientdebugdata)

***

### deviceIndex?

> `optional` **deviceIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:13069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13069)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`deviceIndex`](../interfaces/ISyncdPatch.md#deviceindex)

***

### exitCode?

> `optional` **exitCode**: `null` \| [`IExitCode`](../interfaces/IExitCode.md)

Defined in: [WAProto/index.d.ts:13068](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13068)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`exitCode`](../interfaces/ISyncdPatch.md#exitcode)

***

### externalMutations?

> `optional` **externalMutations**: `null` \| [`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:13064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13064)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`externalMutations`](../interfaces/ISyncdPatch.md#externalmutations)

***

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:13067](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13067)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`keyId`](../interfaces/ISyncdPatch.md#keyid)

***

### mutations

> **mutations**: [`ISyncdMutation`](../interfaces/ISyncdMutation.md)[]

Defined in: [WAProto/index.d.ts:13063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13063)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`mutations`](../interfaces/ISyncdPatch.md#mutations)

***

### patchMac?

> `optional` **patchMac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13066](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13066)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`patchMac`](../interfaces/ISyncdPatch.md#patchmac)

***

### snapshotMac?

> `optional` **snapshotMac**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13065)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`snapshotMac`](../interfaces/ISyncdPatch.md#snapshotmac)

***

### version?

> `optional` **version**: `null` \| [`ISyncdVersion`](../interfaces/ISyncdVersion.md)

Defined in: [WAProto/index.d.ts:13062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13062)

#### Implementation of

[`ISyncdPatch`](../interfaces/ISyncdPatch.md).[`version`](../interfaces/ISyncdPatch.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13076](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13076)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:13071](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13071)

#### Parameters

##### properties?

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

#### Returns

[`SyncdPatch`](SyncdPatch.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:13073](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13073)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdPatch`](SyncdPatch.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13072)

#### Parameters

##### m

[`ISyncdPatch`](../interfaces/ISyncdPatch.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdPatch`](SyncdPatch.md)

Defined in: [WAProto/index.d.ts:13074](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13074)

#### Parameters

##### d

#### Returns

[`SyncdPatch`](SyncdPatch.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13077](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13077)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13075](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13075)

#### Parameters

##### m

[`SyncdPatch`](SyncdPatch.md)

##### o?

`IConversionOptions`

#### Returns

`object`
