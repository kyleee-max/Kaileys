# Class: AppStateSyncKeyId

Defined in: [WAProto/index.d.ts:5491](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5491)

## Implements

- [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

## Constructors

### new AppStateSyncKeyId()

> **new AppStateSyncKeyId**(`p`?): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:5492](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5492)

#### Parameters

##### p?

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

## Properties

### keyId?

> `optional` **keyId**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5493](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5493)

#### Implementation of

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md).[`keyId`](../interfaces/IAppStateSyncKeyId.md#keyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5499](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5499)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:5494](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5494)

#### Parameters

##### properties?

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:5496](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5496)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5495](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5495)

#### Parameters

##### m

[`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateSyncKeyId`](AppStateSyncKeyId.md)

Defined in: [WAProto/index.d.ts:5497](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5497)

#### Parameters

##### d

#### Returns

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5500](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5500)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5498](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5498)

#### Parameters

##### m

[`AppStateSyncKeyId`](AppStateSyncKeyId.md)

##### o?

`IConversionOptions`

#### Returns

`object`
