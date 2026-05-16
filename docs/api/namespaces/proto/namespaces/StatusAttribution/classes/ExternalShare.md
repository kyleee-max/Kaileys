# Class: ExternalShare

Defined in: [WAProto/index.d.ts:11165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11165)

## Implements

- [`IExternalShare`](../interfaces/IExternalShare.md)

## Constructors

### new ExternalShare()

> **new ExternalShare**(`p`?): [`ExternalShare`](ExternalShare.md)

Defined in: [WAProto/index.d.ts:11166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11166)

#### Parameters

##### p?

[`IExternalShare`](../interfaces/IExternalShare.md)

#### Returns

[`ExternalShare`](ExternalShare.md)

## Properties

### actionFallbackUrl?

> `optional` **actionFallbackUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11170](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11170)

#### Implementation of

[`IExternalShare`](../interfaces/IExternalShare.md).[`actionFallbackUrl`](../interfaces/IExternalShare.md#actionfallbackurl)

***

### actionUrl?

> `optional` **actionUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11167)

#### Implementation of

[`IExternalShare`](../interfaces/IExternalShare.md).[`actionUrl`](../interfaces/IExternalShare.md#actionurl)

***

### duration?

> `optional` **duration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11169](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11169)

#### Implementation of

[`IExternalShare`](../interfaces/IExternalShare.md).[`duration`](../interfaces/IExternalShare.md#duration)

***

### source?

> `optional` **source**: `null` \| [`Source`](../namespaces/ExternalShare/enumerations/Source.md)

Defined in: [WAProto/index.d.ts:11168](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11168)

#### Implementation of

[`IExternalShare`](../interfaces/IExternalShare.md).[`source`](../interfaces/IExternalShare.md#source)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11176)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ExternalShare`](ExternalShare.md)

Defined in: [WAProto/index.d.ts:11171](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11171)

#### Parameters

##### properties?

[`IExternalShare`](../interfaces/IExternalShare.md)

#### Returns

[`ExternalShare`](ExternalShare.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ExternalShare`](ExternalShare.md)

Defined in: [WAProto/index.d.ts:11173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11173)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ExternalShare`](ExternalShare.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11172)

#### Parameters

##### m

[`IExternalShare`](../interfaces/IExternalShare.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ExternalShare`](ExternalShare.md)

Defined in: [WAProto/index.d.ts:11174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11174)

#### Parameters

##### d

#### Returns

[`ExternalShare`](ExternalShare.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11177)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11175)

#### Parameters

##### m

[`ExternalShare`](ExternalShare.md)

##### o?

`IConversionOptions`

#### Returns

`object`
