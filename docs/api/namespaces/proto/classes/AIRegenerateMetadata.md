# Class: AIRegenerateMetadata

Defined in: [WAProto/index.d.ts:206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L206)

## Implements

- [`IAIRegenerateMetadata`](../interfaces/IAIRegenerateMetadata.md)

## Constructors

### new AIRegenerateMetadata()

> **new AIRegenerateMetadata**(`p`?): [`AIRegenerateMetadata`](AIRegenerateMetadata.md)

Defined in: [WAProto/index.d.ts:207](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L207)

#### Parameters

##### p?

[`IAIRegenerateMetadata`](../interfaces/IAIRegenerateMetadata.md)

#### Returns

[`AIRegenerateMetadata`](AIRegenerateMetadata.md)

## Properties

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:208](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L208)

#### Implementation of

[`IAIRegenerateMetadata`](../interfaces/IAIRegenerateMetadata.md).[`messageKey`](../interfaces/IAIRegenerateMetadata.md#messagekey)

***

### responseTimestampMs?

> `optional` **responseTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:209](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L209)

#### Implementation of

[`IAIRegenerateMetadata`](../interfaces/IAIRegenerateMetadata.md).[`responseTimestampMs`](../interfaces/IAIRegenerateMetadata.md#responsetimestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:215](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L215)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRegenerateMetadata`](AIRegenerateMetadata.md)

Defined in: [WAProto/index.d.ts:210](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L210)

#### Parameters

##### properties?

[`IAIRegenerateMetadata`](../interfaces/IAIRegenerateMetadata.md)

#### Returns

[`AIRegenerateMetadata`](AIRegenerateMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRegenerateMetadata`](AIRegenerateMetadata.md)

Defined in: [WAProto/index.d.ts:212](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L212)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRegenerateMetadata`](AIRegenerateMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:211](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L211)

#### Parameters

##### m

[`IAIRegenerateMetadata`](../interfaces/IAIRegenerateMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRegenerateMetadata`](AIRegenerateMetadata.md)

Defined in: [WAProto/index.d.ts:213](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L213)

#### Parameters

##### d

#### Returns

[`AIRegenerateMetadata`](AIRegenerateMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:216](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L216)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:214](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L214)

#### Parameters

##### m

[`AIRegenerateMetadata`](AIRegenerateMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
