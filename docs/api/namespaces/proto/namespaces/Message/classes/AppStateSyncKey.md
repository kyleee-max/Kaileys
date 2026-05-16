# Class: AppStateSyncKey

Defined in: [WAProto/index.d.ts:5434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5434)

## Implements

- [`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

## Constructors

### new AppStateSyncKey()

> **new AppStateSyncKey**(`p`?): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:5435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5435)

#### Parameters

##### p?

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

## Properties

### keyData?

> `optional` **keyData**: `null` \| [`IAppStateSyncKeyData`](../interfaces/IAppStateSyncKeyData.md)

Defined in: [WAProto/index.d.ts:5437](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5437)

#### Implementation of

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md).[`keyData`](../interfaces/IAppStateSyncKey.md#keydata)

***

### keyId?

> `optional` **keyId**: `null` \| [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:5436](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5436)

#### Implementation of

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md).[`keyId`](../interfaces/IAppStateSyncKey.md#keyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5443)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:5438](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5438)

#### Parameters

##### properties?

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:5440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5440)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5439)

#### Parameters

##### m

[`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateSyncKey`](AppStateSyncKey.md)

Defined in: [WAProto/index.d.ts:5441](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5441)

#### Parameters

##### d

#### Returns

[`AppStateSyncKey`](AppStateSyncKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5444)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5442](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5442)

#### Parameters

##### m

[`AppStateSyncKey`](AppStateSyncKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
