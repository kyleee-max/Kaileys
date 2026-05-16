# Class: URLButton

Defined in: [WAProto/index.d.ts:13238](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13238)

## Implements

- [`IURLButton`](../interfaces/IURLButton.md)

## Constructors

### new URLButton()

> **new URLButton**(`p`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:13239](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13239)

#### Parameters

##### p?

[`IURLButton`](../interfaces/IURLButton.md)

#### Returns

[`URLButton`](URLButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:13240](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13240)

#### Implementation of

[`IURLButton`](../interfaces/IURLButton.md).[`displayText`](../interfaces/IURLButton.md#displaytext)

***

### url?

> `optional` **url**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:13241](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13241)

#### Implementation of

[`IURLButton`](../interfaces/IURLButton.md).[`url`](../interfaces/IURLButton.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13247](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13247)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:13242](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13242)

#### Parameters

##### properties?

[`IURLButton`](../interfaces/IURLButton.md)

#### Returns

[`URLButton`](URLButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:13244](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13244)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`URLButton`](URLButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13243](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13243)

#### Parameters

##### m

[`IURLButton`](../interfaces/IURLButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`URLButton`](URLButton.md)

Defined in: [WAProto/index.d.ts:13245](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13245)

#### Parameters

##### d

#### Returns

[`URLButton`](URLButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13248](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13248)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13246](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13246)

#### Parameters

##### m

[`URLButton`](URLButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
