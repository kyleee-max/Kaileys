# Class: AIRichResponseReelItem

Defined in: [WAProto/index.d.ts:311](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L311)

## Implements

- [`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md)

## Constructors

### new AIRichResponseReelItem()

> **new AIRichResponseReelItem**(`p`?): [`AIRichResponseReelItem`](AIRichResponseReelItem.md)

Defined in: [WAProto/index.d.ts:312](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L312)

#### Parameters

##### p?

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md)

#### Returns

[`AIRichResponseReelItem`](AIRichResponseReelItem.md)

## Properties

### profileIconUrl?

> `optional` **profileIconUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:314](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L314)

#### Implementation of

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md).[`profileIconUrl`](../interfaces/IAIRichResponseReelItem.md#profileiconurl)

***

### thumbnailUrl?

> `optional` **thumbnailUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:315](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L315)

#### Implementation of

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md).[`thumbnailUrl`](../interfaces/IAIRichResponseReelItem.md#thumbnailurl)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:313](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L313)

#### Implementation of

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md).[`title`](../interfaces/IAIRichResponseReelItem.md#title)

***

### videoUrl?

> `optional` **videoUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:316](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L316)

#### Implementation of

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md).[`videoUrl`](../interfaces/IAIRichResponseReelItem.md#videourl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:322](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L322)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseReelItem`](AIRichResponseReelItem.md)

Defined in: [WAProto/index.d.ts:317](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L317)

#### Parameters

##### properties?

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md)

#### Returns

[`AIRichResponseReelItem`](AIRichResponseReelItem.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseReelItem`](AIRichResponseReelItem.md)

Defined in: [WAProto/index.d.ts:319](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L319)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseReelItem`](AIRichResponseReelItem.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L318)

#### Parameters

##### m

[`IAIRichResponseReelItem`](../interfaces/IAIRichResponseReelItem.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseReelItem`](AIRichResponseReelItem.md)

Defined in: [WAProto/index.d.ts:320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L320)

#### Parameters

##### d

#### Returns

[`AIRichResponseReelItem`](AIRichResponseReelItem.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:323](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L323)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:321](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L321)

#### Parameters

##### m

[`AIRichResponseReelItem`](AIRichResponseReelItem.md)

##### o?

`IConversionOptions`

#### Returns

`object`
