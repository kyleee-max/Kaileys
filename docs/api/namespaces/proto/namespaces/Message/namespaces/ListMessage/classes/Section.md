# Class: Section

Defined in: [WAProto/index.d.ts:7269](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7269)

## Implements

- [`ISection`](../interfaces/ISection.md)

## Constructors

### new Section()

> **new Section**(`p`?): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:7270](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7270)

#### Parameters

##### p?

[`ISection`](../interfaces/ISection.md)

#### Returns

[`Section`](Section.md)

## Properties

### rows

> **rows**: [`IRow`](../interfaces/IRow.md)[]

Defined in: [WAProto/index.d.ts:7272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7272)

#### Implementation of

[`ISection`](../interfaces/ISection.md).[`rows`](../interfaces/ISection.md#rows)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7271](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7271)

#### Implementation of

[`ISection`](../interfaces/ISection.md).[`title`](../interfaces/ISection.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7278](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7278)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:7273](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7273)

#### Parameters

##### properties?

[`ISection`](../interfaces/ISection.md)

#### Returns

[`Section`](Section.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:7275](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7275)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Section`](Section.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7274](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7274)

#### Parameters

##### m

[`ISection`](../interfaces/ISection.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Section`](Section.md)

Defined in: [WAProto/index.d.ts:7276](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7276)

#### Parameters

##### d

#### Returns

[`Section`](Section.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7279](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7279)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7277](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7277)

#### Parameters

##### m

[`Section`](Section.md)

##### o?

`IConversionOptions`

#### Returns

`object`
