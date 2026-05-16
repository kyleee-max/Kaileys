# Class: PrimaryFeature

Defined in: [WAProto/index.d.ts:12529](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12529)

## Implements

- [`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

## Constructors

### new PrimaryFeature()

> **new PrimaryFeature**(`p`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:12530](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12530)

#### Parameters

##### p?

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

## Properties

### flags

> **flags**: `string`[]

Defined in: [WAProto/index.d.ts:12531](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12531)

#### Implementation of

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md).[`flags`](../interfaces/IPrimaryFeature.md#flags)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12537](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12537)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:12532](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12532)

#### Parameters

##### properties?

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:12534](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12534)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12533](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12533)

#### Parameters

##### m

[`IPrimaryFeature`](../interfaces/IPrimaryFeature.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PrimaryFeature`](PrimaryFeature.md)

Defined in: [WAProto/index.d.ts:12535](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12535)

#### Parameters

##### d

#### Returns

[`PrimaryFeature`](PrimaryFeature.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12538](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12538)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12536](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12536)

#### Parameters

##### m

[`PrimaryFeature`](PrimaryFeature.md)

##### o?

`IConversionOptions`

#### Returns

`object`
