# Class: SideBySideMetadata

Defined in: [WAProto/index.d.ts:2285](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2285)

## Implements

- [`ISideBySideMetadata`](../interfaces/ISideBySideMetadata.md)

## Constructors

### new SideBySideMetadata()

> **new SideBySideMetadata**(`p`?): [`SideBySideMetadata`](SideBySideMetadata.md)

Defined in: [WAProto/index.d.ts:2286](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2286)

#### Parameters

##### p?

[`ISideBySideMetadata`](../interfaces/ISideBySideMetadata.md)

#### Returns

[`SideBySideMetadata`](SideBySideMetadata.md)

## Properties

### primaryResponseId?

> `optional` **primaryResponseId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2287](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2287)

#### Implementation of

[`ISideBySideMetadata`](../interfaces/ISideBySideMetadata.md).[`primaryResponseId`](../interfaces/ISideBySideMetadata.md#primaryresponseid)

***

### surveyCtaHasRendered?

> `optional` **surveyCtaHasRendered**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2288](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2288)

#### Implementation of

[`ISideBySideMetadata`](../interfaces/ISideBySideMetadata.md).[`surveyCtaHasRendered`](../interfaces/ISideBySideMetadata.md#surveyctahasrendered)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2294](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2294)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SideBySideMetadata`](SideBySideMetadata.md)

Defined in: [WAProto/index.d.ts:2289](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2289)

#### Parameters

##### properties?

[`ISideBySideMetadata`](../interfaces/ISideBySideMetadata.md)

#### Returns

[`SideBySideMetadata`](SideBySideMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SideBySideMetadata`](SideBySideMetadata.md)

Defined in: [WAProto/index.d.ts:2291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2291)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SideBySideMetadata`](SideBySideMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2290](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2290)

#### Parameters

##### m

[`ISideBySideMetadata`](../interfaces/ISideBySideMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SideBySideMetadata`](SideBySideMetadata.md)

Defined in: [WAProto/index.d.ts:2292](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2292)

#### Parameters

##### d

#### Returns

[`SideBySideMetadata`](SideBySideMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2295](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2295)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2293](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2293)

#### Parameters

##### m

[`SideBySideMetadata`](SideBySideMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
