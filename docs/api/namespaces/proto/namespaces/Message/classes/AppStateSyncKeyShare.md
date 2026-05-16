# Class: AppStateSyncKeyShare

Defined in: [WAProto/index.d.ts:5523](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5523)

## Implements

- [`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

## Constructors

### new AppStateSyncKeyShare()

> **new AppStateSyncKeyShare**(`p`?): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:5524](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5524)

#### Parameters

##### p?

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

## Properties

### keys

> **keys**: [`IAppStateSyncKey`](../interfaces/IAppStateSyncKey.md)[]

Defined in: [WAProto/index.d.ts:5525](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5525)

#### Implementation of

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md).[`keys`](../interfaces/IAppStateSyncKeyShare.md#keys)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5531](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5531)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:5526](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5526)

#### Parameters

##### properties?

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:5528](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5528)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5527](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5527)

#### Parameters

##### m

[`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:5529](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5529)

#### Parameters

##### d

#### Returns

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5532](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5532)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5530](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5530)

#### Parameters

##### m

[`AppStateSyncKeyShare`](AppStateSyncKeyShare.md)

##### o?

`IConversionOptions`

#### Returns

`object`
