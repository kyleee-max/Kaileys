# Class: InThreadSurveyOption

Defined in: [WAProto/index.d.ts:4768](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4768)

## Implements

- [`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md)

## Constructors

### new InThreadSurveyOption()

> **new InThreadSurveyOption**(`p`?): [`InThreadSurveyOption`](InThreadSurveyOption.md)

Defined in: [WAProto/index.d.ts:4769](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4769)

#### Parameters

##### p?

[`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md)

#### Returns

[`InThreadSurveyOption`](InThreadSurveyOption.md)

## Properties

### numericValue?

> `optional` **numericValue**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4771)

#### Implementation of

[`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md).[`numericValue`](../interfaces/IInThreadSurveyOption.md#numericvalue)

***

### stringValue?

> `optional` **stringValue**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4770](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4770)

#### Implementation of

[`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md).[`stringValue`](../interfaces/IInThreadSurveyOption.md#stringvalue)

***

### textTranslated?

> `optional` **textTranslated**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4772)

#### Implementation of

[`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md).[`textTranslated`](../interfaces/IInThreadSurveyOption.md#texttranslated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4778](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4778)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InThreadSurveyOption`](InThreadSurveyOption.md)

Defined in: [WAProto/index.d.ts:4773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4773)

#### Parameters

##### properties?

[`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md)

#### Returns

[`InThreadSurveyOption`](InThreadSurveyOption.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InThreadSurveyOption`](InThreadSurveyOption.md)

Defined in: [WAProto/index.d.ts:4775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4775)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InThreadSurveyOption`](InThreadSurveyOption.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4774)

#### Parameters

##### m

[`IInThreadSurveyOption`](../interfaces/IInThreadSurveyOption.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InThreadSurveyOption`](InThreadSurveyOption.md)

Defined in: [WAProto/index.d.ts:4776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4776)

#### Parameters

##### d

#### Returns

[`InThreadSurveyOption`](InThreadSurveyOption.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4779](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4779)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4777](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4777)

#### Parameters

##### m

[`InThreadSurveyOption`](InThreadSurveyOption.md)

##### o?

`IConversionOptions`

#### Returns

`object`
