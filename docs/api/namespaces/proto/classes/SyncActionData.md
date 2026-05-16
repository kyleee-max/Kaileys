# Class: SyncActionData

Defined in: [WAProto/index.d.ts:11412](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11412)

## Implements

- [`ISyncActionData`](../interfaces/ISyncActionData.md)

## Constructors

### new SyncActionData()

> **new SyncActionData**(`p`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:11413](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11413)

#### Parameters

##### p?

[`ISyncActionData`](../interfaces/ISyncActionData.md)

#### Returns

[`SyncActionData`](SyncActionData.md)

## Properties

### index?

> `optional` **index**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11414](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11414)

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`index`](../interfaces/ISyncActionData.md#index)

***

### padding?

> `optional` **padding**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11416)

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`padding`](../interfaces/ISyncActionData.md#padding)

***

### value?

> `optional` **value**: `null` \| [`ISyncActionValue`](../interfaces/ISyncActionValue.md)

Defined in: [WAProto/index.d.ts:11415](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11415)

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`value`](../interfaces/ISyncActionData.md#value)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11417)

#### Implementation of

[`ISyncActionData`](../interfaces/ISyncActionData.md).[`version`](../interfaces/ISyncActionData.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11423)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:11418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11418)

#### Parameters

##### properties?

[`ISyncActionData`](../interfaces/ISyncActionData.md)

#### Returns

[`SyncActionData`](SyncActionData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:11420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11420)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncActionData`](SyncActionData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11419)

#### Parameters

##### m

[`ISyncActionData`](../interfaces/ISyncActionData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncActionData`](SyncActionData.md)

Defined in: [WAProto/index.d.ts:11421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11421)

#### Parameters

##### d

#### Returns

[`SyncActionData`](SyncActionData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11424)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11422)

#### Parameters

##### m

[`SyncActionData`](SyncActionData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
