# Class: AIRichResponseTableRow

Defined in: [WAProto/index.d.ts:637](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L637)

## Implements

- [`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

## Constructors

### new AIRichResponseTableRow()

> **new AIRichResponseTableRow**(`p`?): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:638](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L638)

#### Parameters

##### p?

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

## Properties

### isHeading?

> `optional` **isHeading**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:640](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L640)

#### Implementation of

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md).[`isHeading`](../interfaces/IAIRichResponseTableRow.md#isheading)

***

### items

> **items**: `string`[]

Defined in: [WAProto/index.d.ts:639](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L639)

#### Implementation of

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md).[`items`](../interfaces/IAIRichResponseTableRow.md#items)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:646](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L646)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L641)

#### Parameters

##### properties?

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:643](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L643)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:642](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L642)

#### Parameters

##### m

[`IAIRichResponseTableRow`](../interfaces/IAIRichResponseTableRow.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseTableRow`](AIRichResponseTableRow.md)

Defined in: [WAProto/index.d.ts:644](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L644)

#### Parameters

##### d

#### Returns

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:647](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L647)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:645](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L645)

#### Parameters

##### m

[`AIRichResponseTableRow`](AIRichResponseTableRow.md)

##### o?

`IConversionOptions`

#### Returns

`object`
