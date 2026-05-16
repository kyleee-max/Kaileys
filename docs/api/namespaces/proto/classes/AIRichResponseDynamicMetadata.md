# Class: AIRichResponseDynamicMetadata

Defined in: [WAProto/index.d.ts:339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L339)

## Implements

- [`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

## Constructors

### new AIRichResponseDynamicMetadata()

> **new AIRichResponseDynamicMetadata**(`p`?): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L340)

#### Parameters

##### p?

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

## Properties

### loopCount?

> `optional` **loopCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L344)

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`loopCount`](../interfaces/IAIRichResponseDynamicMetadata.md#loopcount)

***

### type?

> `optional` **type**: `null` \| [`AIRichResponseDynamicMetadataType`](../namespaces/AIRichResponseDynamicMetadata/enumerations/AIRichResponseDynamicMetadataType.md)

Defined in: [WAProto/index.d.ts:341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L341)

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`type`](../interfaces/IAIRichResponseDynamicMetadata.md#type)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:343](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L343)

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`url`](../interfaces/IAIRichResponseDynamicMetadata.md#url)

***

### version?

> `optional` **version**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L342)

#### Implementation of

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md).[`version`](../interfaces/IAIRichResponseDynamicMetadata.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L350)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L345)

#### Parameters

##### properties?

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L347)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:346](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L346)

#### Parameters

##### m

[`IAIRichResponseDynamicMetadata`](../interfaces/IAIRichResponseDynamicMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

Defined in: [WAProto/index.d.ts:348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L348)

#### Parameters

##### d

#### Returns

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L351)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L349)

#### Parameters

##### m

[`AIRichResponseDynamicMetadata`](AIRichResponseDynamicMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
