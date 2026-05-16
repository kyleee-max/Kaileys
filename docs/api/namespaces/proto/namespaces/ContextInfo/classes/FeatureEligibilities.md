# Class: FeatureEligibilities

Defined in: [WAProto/index.d.ts:3446](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3446)

## Implements

- [`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md)

## Constructors

### new FeatureEligibilities()

> **new FeatureEligibilities**(`p`?): [`FeatureEligibilities`](FeatureEligibilities.md)

Defined in: [WAProto/index.d.ts:3447](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3447)

#### Parameters

##### p?

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md)

#### Returns

[`FeatureEligibilities`](FeatureEligibilities.md)

## Properties

### canBeReshared?

> `optional` **canBeReshared**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3451](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3451)

#### Implementation of

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md).[`canBeReshared`](../interfaces/IFeatureEligibilities.md#canbereshared)

***

### cannotBeRanked?

> `optional` **cannotBeRanked**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3449](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3449)

#### Implementation of

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md).[`cannotBeRanked`](../interfaces/IFeatureEligibilities.md#cannotberanked)

***

### cannotBeReactedTo?

> `optional` **cannotBeReactedTo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3448](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3448)

#### Implementation of

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md).[`cannotBeReactedTo`](../interfaces/IFeatureEligibilities.md#cannotbereactedto)

***

### canReceiveMultiReact?

> `optional` **canReceiveMultiReact**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3452](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3452)

#### Implementation of

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md).[`canReceiveMultiReact`](../interfaces/IFeatureEligibilities.md#canreceivemultireact)

***

### canRequestFeedback?

> `optional` **canRequestFeedback**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3450](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3450)

#### Implementation of

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md).[`canRequestFeedback`](../interfaces/IFeatureEligibilities.md#canrequestfeedback)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3458)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`FeatureEligibilities`](FeatureEligibilities.md)

Defined in: [WAProto/index.d.ts:3453](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3453)

#### Parameters

##### properties?

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md)

#### Returns

[`FeatureEligibilities`](FeatureEligibilities.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`FeatureEligibilities`](FeatureEligibilities.md)

Defined in: [WAProto/index.d.ts:3455](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3455)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`FeatureEligibilities`](FeatureEligibilities.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3454](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3454)

#### Parameters

##### m

[`IFeatureEligibilities`](../interfaces/IFeatureEligibilities.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`FeatureEligibilities`](FeatureEligibilities.md)

Defined in: [WAProto/index.d.ts:3456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3456)

#### Parameters

##### d

#### Returns

[`FeatureEligibilities`](FeatureEligibilities.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3459)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3457)

#### Parameters

##### m

[`FeatureEligibilities`](FeatureEligibilities.md)

##### o?

`IConversionOptions`

#### Returns

`object`
