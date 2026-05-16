# Class: CarouselMessage

Defined in: [WAProto/index.d.ts:6789](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6789)

## Implements

- [`ICarouselMessage`](../interfaces/ICarouselMessage.md)

## Constructors

### new CarouselMessage()

> **new CarouselMessage**(`p`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:6790](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6790)

#### Parameters

##### p?

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

#### Returns

[`CarouselMessage`](CarouselMessage.md)

## Properties

### cards

> **cards**: [`IInteractiveMessage`](../../../interfaces/IInteractiveMessage.md)[]

Defined in: [WAProto/index.d.ts:6791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6791)

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`cards`](../interfaces/ICarouselMessage.md#cards)

***

### carouselCardType?

> `optional` **carouselCardType**: `null` \| [`CarouselCardType`](../namespaces/CarouselMessage/enumerations/CarouselCardType.md)

Defined in: [WAProto/index.d.ts:6793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6793)

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`carouselCardType`](../interfaces/ICarouselMessage.md#carouselcardtype)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6792)

#### Implementation of

[`ICarouselMessage`](../interfaces/ICarouselMessage.md).[`messageVersion`](../interfaces/ICarouselMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6799](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6799)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:6794](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6794)

#### Parameters

##### properties?

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

#### Returns

[`CarouselMessage`](CarouselMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:6796](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6796)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CarouselMessage`](CarouselMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6795](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6795)

#### Parameters

##### m

[`ICarouselMessage`](../interfaces/ICarouselMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CarouselMessage`](CarouselMessage.md)

Defined in: [WAProto/index.d.ts:6797](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6797)

#### Parameters

##### d

#### Returns

[`CarouselMessage`](CarouselMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6800)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6798)

#### Parameters

##### m

[`CarouselMessage`](CarouselMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
