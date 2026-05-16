# Class: LocaleSetting

Defined in: [WAProto/index.d.ts:12172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12172)

## Implements

- [`ILocaleSetting`](../interfaces/ILocaleSetting.md)

## Constructors

### new LocaleSetting()

> **new LocaleSetting**(`p`?): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:12173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12173)

#### Parameters

##### p?

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

#### Returns

[`LocaleSetting`](LocaleSetting.md)

## Properties

### locale?

> `optional` **locale**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12174)

#### Implementation of

[`ILocaleSetting`](../interfaces/ILocaleSetting.md).[`locale`](../interfaces/ILocaleSetting.md#locale)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12180)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:12175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12175)

#### Parameters

##### properties?

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

#### Returns

[`LocaleSetting`](LocaleSetting.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:12177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12177)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LocaleSetting`](LocaleSetting.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12176)

#### Parameters

##### m

[`ILocaleSetting`](../interfaces/ILocaleSetting.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LocaleSetting`](LocaleSetting.md)

Defined in: [WAProto/index.d.ts:12178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12178)

#### Parameters

##### d

#### Returns

[`LocaleSetting`](LocaleSetting.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12181)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12179)

#### Parameters

##### m

[`LocaleSetting`](LocaleSetting.md)

##### o?

`IConversionOptions`

#### Returns

`object`
