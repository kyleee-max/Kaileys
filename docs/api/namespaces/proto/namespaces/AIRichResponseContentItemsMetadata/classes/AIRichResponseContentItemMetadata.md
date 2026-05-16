# Class: AIRichResponseContentItemMetadata

Defined in: [WAProto/index.d.ts:291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L291)

## Implements

- [`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

## Constructors

### new AIRichResponseContentItemMetadata()

> **new AIRichResponseContentItemMetadata**(`p`?): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:292](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L292)

#### Parameters

##### p?

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

## Properties

### aIRichResponseContentItem?

> `optional` **aIRichResponseContentItem**: `"reelItem"`

Defined in: [WAProto/index.d.ts:294](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L294)

***

### reelItem?

> `optional` **reelItem**: `null` \| [`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md)

Defined in: [WAProto/index.d.ts:293](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L293)

#### Implementation of

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md).[`reelItem`](../interfaces/IAIRichResponseContentItemMetadata.md#reelitem)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:300](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L300)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:295](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L295)

#### Parameters

##### properties?

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:297](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L297)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:296](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L296)

#### Parameters

##### m

[`IAIRichResponseContentItemMetadata`](../interfaces/IAIRichResponseContentItemMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

Defined in: [WAProto/index.d.ts:298](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L298)

#### Parameters

##### d

#### Returns

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:301](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L301)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:299](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L299)

#### Parameters

##### m

[`AIRichResponseContentItemMetadata`](AIRichResponseContentItemMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
