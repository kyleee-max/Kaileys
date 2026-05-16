# Class: AIRichResponseMapMetadata

Defined in: [WAProto/index.d.ts:494](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L494)

## Implements

- [`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md)

## Constructors

### new AIRichResponseMapMetadata()

> **new AIRichResponseMapMetadata**(`p`?): [`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

Defined in: [WAProto/index.d.ts:495](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L495)

#### Parameters

##### p?

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md)

#### Returns

[`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

## Properties

### annotations

> **annotations**: [`IAIRichResponseMapAnnotation`](../namespaces/AIRichResponseMapMetadata/interfaces/IAIRichResponseMapAnnotation.md)[]

Defined in: [WAProto/index.d.ts:500](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L500)

#### Implementation of

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md).[`annotations`](../interfaces/IAIRichResponseMapMetadata.md#annotations)

***

### centerLatitude?

> `optional` **centerLatitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:496](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L496)

#### Implementation of

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md).[`centerLatitude`](../interfaces/IAIRichResponseMapMetadata.md#centerlatitude)

***

### centerLongitude?

> `optional` **centerLongitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:497](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L497)

#### Implementation of

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md).[`centerLongitude`](../interfaces/IAIRichResponseMapMetadata.md#centerlongitude)

***

### latitudeDelta?

> `optional` **latitudeDelta**: `null` \| `number`

Defined in: [WAProto/index.d.ts:498](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L498)

#### Implementation of

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md).[`latitudeDelta`](../interfaces/IAIRichResponseMapMetadata.md#latitudedelta)

***

### longitudeDelta?

> `optional` **longitudeDelta**: `null` \| `number`

Defined in: [WAProto/index.d.ts:499](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L499)

#### Implementation of

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md).[`longitudeDelta`](../interfaces/IAIRichResponseMapMetadata.md#longitudedelta)

***

### showInfoList?

> `optional` **showInfoList**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:501](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L501)

#### Implementation of

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md).[`showInfoList`](../interfaces/IAIRichResponseMapMetadata.md#showinfolist)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:507](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L507)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

Defined in: [WAProto/index.d.ts:502](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L502)

#### Parameters

##### properties?

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md)

#### Returns

[`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

Defined in: [WAProto/index.d.ts:504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L504)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L503)

#### Parameters

##### m

[`IAIRichResponseMapMetadata`](../interfaces/IAIRichResponseMapMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

Defined in: [WAProto/index.d.ts:505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L505)

#### Parameters

##### d

#### Returns

[`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:508](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L508)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L506)

#### Parameters

##### m

[`AIRichResponseMapMetadata`](AIRichResponseMapMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
