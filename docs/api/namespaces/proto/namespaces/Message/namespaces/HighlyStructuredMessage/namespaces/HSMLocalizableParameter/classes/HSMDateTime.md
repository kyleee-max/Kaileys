# Class: HSMDateTime

Defined in: [WAProto/index.d.ts:6477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6477)

## Implements

- [`IHSMDateTime`](../interfaces/IHSMDateTime.md)

## Constructors

### new HSMDateTime()

> **new HSMDateTime**(`p`?): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:6478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6478)

#### Parameters

##### p?

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

#### Returns

[`HSMDateTime`](HSMDateTime.md)

## Properties

### component?

> `optional` **component**: `null` \| [`IHSMDateTimeComponent`](../namespaces/HSMDateTime/interfaces/IHSMDateTimeComponent.md)

Defined in: [WAProto/index.d.ts:6479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6479)

#### Implementation of

[`IHSMDateTime`](../interfaces/IHSMDateTime.md).[`component`](../interfaces/IHSMDateTime.md#component)

***

### datetimeOneof?

> `optional` **datetimeOneof**: `"component"` \| `"unixEpoch"`

Defined in: [WAProto/index.d.ts:6481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6481)

***

### unixEpoch?

> `optional` **unixEpoch**: `null` \| [`IHSMDateTimeUnixEpoch`](../namespaces/HSMDateTime/interfaces/IHSMDateTimeUnixEpoch.md)

Defined in: [WAProto/index.d.ts:6480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6480)

#### Implementation of

[`IHSMDateTime`](../interfaces/IHSMDateTime.md).[`unixEpoch`](../interfaces/IHSMDateTime.md#unixepoch)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6487)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:6482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6482)

#### Parameters

##### properties?

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

#### Returns

[`HSMDateTime`](HSMDateTime.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:6484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6484)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HSMDateTime`](HSMDateTime.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6483)

#### Parameters

##### m

[`IHSMDateTime`](../interfaces/IHSMDateTime.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HSMDateTime`](HSMDateTime.md)

Defined in: [WAProto/index.d.ts:6485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6485)

#### Parameters

##### d

#### Returns

[`HSMDateTime`](HSMDateTime.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6488)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6486)

#### Parameters

##### m

[`HSMDateTime`](HSMDateTime.md)

##### o?

`IConversionOptions`

#### Returns

`object`
