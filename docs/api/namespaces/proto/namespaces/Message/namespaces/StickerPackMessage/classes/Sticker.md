# Class: Sticker

Defined in: [WAProto/index.d.ts:9114](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9114)

## Implements

- [`ISticker`](../interfaces/ISticker.md)

## Constructors

### new Sticker()

> **new Sticker**(`p`?): [`Sticker`](Sticker.md)

Defined in: [WAProto/index.d.ts:9115](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9115)

#### Parameters

##### p?

[`ISticker`](../interfaces/ISticker.md)

#### Returns

[`Sticker`](Sticker.md)

## Properties

### accessibilityLabel?

> `optional` **accessibilityLabel**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9119)

#### Implementation of

[`ISticker`](../interfaces/ISticker.md).[`accessibilityLabel`](../interfaces/ISticker.md#accessibilitylabel)

***

### emojis

> **emojis**: `string`[]

Defined in: [WAProto/index.d.ts:9118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9118)

#### Implementation of

[`ISticker`](../interfaces/ISticker.md).[`emojis`](../interfaces/ISticker.md#emojis)

***

### fileName?

> `optional` **fileName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9116)

#### Implementation of

[`ISticker`](../interfaces/ISticker.md).[`fileName`](../interfaces/ISticker.md#filename)

***

### isAnimated?

> `optional` **isAnimated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9117)

#### Implementation of

[`ISticker`](../interfaces/ISticker.md).[`isAnimated`](../interfaces/ISticker.md#isanimated)

***

### isLottie?

> `optional` **isLottie**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9120)

#### Implementation of

[`ISticker`](../interfaces/ISticker.md).[`isLottie`](../interfaces/ISticker.md#islottie)

***

### mimetype?

> `optional` **mimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9121)

#### Implementation of

[`ISticker`](../interfaces/ISticker.md).[`mimetype`](../interfaces/ISticker.md#mimetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9127)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Sticker`](Sticker.md)

Defined in: [WAProto/index.d.ts:9122](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9122)

#### Parameters

##### properties?

[`ISticker`](../interfaces/ISticker.md)

#### Returns

[`Sticker`](Sticker.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Sticker`](Sticker.md)

Defined in: [WAProto/index.d.ts:9124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9124)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Sticker`](Sticker.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9123)

#### Parameters

##### m

[`ISticker`](../interfaces/ISticker.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Sticker`](Sticker.md)

Defined in: [WAProto/index.d.ts:9125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9125)

#### Parameters

##### d

#### Returns

[`Sticker`](Sticker.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9128](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9128)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9126)

#### Parameters

##### m

[`Sticker`](Sticker.md)

##### o?

`IConversionOptions`

#### Returns

`object`
