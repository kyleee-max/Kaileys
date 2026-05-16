# Class: MaibaAIFeaturesControlAction

Defined in: [WAProto/index.d.ts:12204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12204)

## Implements

- [`IMaibaAIFeaturesControlAction`](../interfaces/IMaibaAIFeaturesControlAction.md)

## Constructors

### new MaibaAIFeaturesControlAction()

> **new MaibaAIFeaturesControlAction**(`p`?): [`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

Defined in: [WAProto/index.d.ts:12205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12205)

#### Parameters

##### p?

[`IMaibaAIFeaturesControlAction`](../interfaces/IMaibaAIFeaturesControlAction.md)

#### Returns

[`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

## Properties

### aiFeatureStatus?

> `optional` **aiFeatureStatus**: `null` \| [`MaibaAIFeatureStatus`](../namespaces/MaibaAIFeaturesControlAction/enumerations/MaibaAIFeatureStatus.md)

Defined in: [WAProto/index.d.ts:12206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12206)

#### Implementation of

[`IMaibaAIFeaturesControlAction`](../interfaces/IMaibaAIFeaturesControlAction.md).[`aiFeatureStatus`](../interfaces/IMaibaAIFeaturesControlAction.md#aifeaturestatus)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12212](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12212)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

Defined in: [WAProto/index.d.ts:12207](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12207)

#### Parameters

##### properties?

[`IMaibaAIFeaturesControlAction`](../interfaces/IMaibaAIFeaturesControlAction.md)

#### Returns

[`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

Defined in: [WAProto/index.d.ts:12209](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12209)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12208](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12208)

#### Parameters

##### m

[`IMaibaAIFeaturesControlAction`](../interfaces/IMaibaAIFeaturesControlAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

Defined in: [WAProto/index.d.ts:12210](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12210)

#### Parameters

##### d

#### Returns

[`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12213](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12213)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12211](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12211)

#### Parameters

##### m

[`MaibaAIFeaturesControlAction`](MaibaAIFeaturesControlAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
