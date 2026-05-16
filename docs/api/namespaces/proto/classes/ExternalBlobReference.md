# Class: ExternalBlobReference

Defined in: [WAProto/index.d.ts:4219](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4219)

## Implements

- [`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

## Constructors

### new ExternalBlobReference()

> **new ExternalBlobReference**(`p`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:4220](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4220)

#### Parameters

##### p?

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

## Properties

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4222)

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`directPath`](../interfaces/IExternalBlobReference.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4226](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4226)

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileEncSha256`](../interfaces/IExternalBlobReference.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4225](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4225)

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileSha256`](../interfaces/IExternalBlobReference.md#filesha256)

***

### fileSizeBytes?

> `optional` **fileSizeBytes**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4224](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4224)

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`fileSizeBytes`](../interfaces/IExternalBlobReference.md#filesizebytes)

***

### handle?

> `optional` **handle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4223](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4223)

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`handle`](../interfaces/IExternalBlobReference.md#handle)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4221](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4221)

#### Implementation of

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md).[`mediaKey`](../interfaces/IExternalBlobReference.md#mediakey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4232)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:4227](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4227)

#### Parameters

##### properties?

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:4229](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4229)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4228)

#### Parameters

##### m

[`IExternalBlobReference`](../interfaces/IExternalBlobReference.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ExternalBlobReference`](ExternalBlobReference.md)

Defined in: [WAProto/index.d.ts:4230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4230)

#### Parameters

##### d

#### Returns

[`ExternalBlobReference`](ExternalBlobReference.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4233)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4231)

#### Parameters

##### m

[`ExternalBlobReference`](ExternalBlobReference.md)

##### o?

`IConversionOptions`

#### Returns

`object`
