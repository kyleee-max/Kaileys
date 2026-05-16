# Class: AppStateSyncKeyRequest

Defined in: [WAProto/index.d.ts:5507](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5507)

## Implements

- [`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

## Constructors

### new AppStateSyncKeyRequest()

> **new AppStateSyncKeyRequest**(`p`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:5508](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5508)

#### Parameters

##### p?

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

## Properties

### keyIds

> **keyIds**: [`IAppStateSyncKeyId`](../interfaces/IAppStateSyncKeyId.md)[]

Defined in: [WAProto/index.d.ts:5509](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5509)

#### Implementation of

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md).[`keyIds`](../interfaces/IAppStateSyncKeyRequest.md#keyids)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5515](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5515)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:5510](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5510)

#### Parameters

##### properties?

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:5512](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5512)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5511](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5511)

#### Parameters

##### m

[`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:5513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5513)

#### Parameters

##### d

#### Returns

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5516](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5516)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5514](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5514)

#### Parameters

##### m

[`AppStateSyncKeyRequest`](AppStateSyncKeyRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
