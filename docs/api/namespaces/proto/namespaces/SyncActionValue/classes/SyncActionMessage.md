# Class: SyncActionMessage

Defined in: [WAProto/index.d.ts:12827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12827)

## Implements

- [`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

## Constructors

### new SyncActionMessage()

> **new SyncActionMessage**(`p`?): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:12828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12828)

#### Parameters

##### p?

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:12829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12829)

#### Implementation of

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md).[`key`](../interfaces/ISyncActionMessage.md#key)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12830)

#### Implementation of

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md).[`timestamp`](../interfaces/ISyncActionMessage.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12836](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12836)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:12831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12831)

#### Parameters

##### properties?

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:12833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12833)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12832)

#### Parameters

##### m

[`ISyncActionMessage`](../interfaces/ISyncActionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncActionMessage`](SyncActionMessage.md)

Defined in: [WAProto/index.d.ts:12834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12834)

#### Parameters

##### d

#### Returns

[`SyncActionMessage`](SyncActionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12837](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12837)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12835)

#### Parameters

##### m

[`SyncActionMessage`](SyncActionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
