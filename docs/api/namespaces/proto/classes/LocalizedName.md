# Class: LocalizedName

Defined in: [WAProto/index.d.ts:5059](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5059)

## Implements

- [`ILocalizedName`](../interfaces/ILocalizedName.md)

## Constructors

### new LocalizedName()

> **new LocalizedName**(`p`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:5060](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5060)

#### Parameters

##### p?

[`ILocalizedName`](../interfaces/ILocalizedName.md)

#### Returns

[`LocalizedName`](LocalizedName.md)

## Properties

### lc?

> `optional` **lc**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5062)

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`lc`](../interfaces/ILocalizedName.md#lc)

***

### lg?

> `optional` **lg**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5061](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5061)

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`lg`](../interfaces/ILocalizedName.md#lg)

***

### verifiedName?

> `optional` **verifiedName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5063)

#### Implementation of

[`ILocalizedName`](../interfaces/ILocalizedName.md).[`verifiedName`](../interfaces/ILocalizedName.md#verifiedname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5069)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:5064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5064)

#### Parameters

##### properties?

[`ILocalizedName`](../interfaces/ILocalizedName.md)

#### Returns

[`LocalizedName`](LocalizedName.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:5066](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5066)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LocalizedName`](LocalizedName.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5065)

#### Parameters

##### m

[`ILocalizedName`](../interfaces/ILocalizedName.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LocalizedName`](LocalizedName.md)

Defined in: [WAProto/index.d.ts:5067](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5067)

#### Parameters

##### d

#### Returns

[`LocalizedName`](LocalizedName.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5070)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5068](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5068)

#### Parameters

##### m

[`LocalizedName`](LocalizedName.md)

##### o?

`IConversionOptions`

#### Returns

`object`
