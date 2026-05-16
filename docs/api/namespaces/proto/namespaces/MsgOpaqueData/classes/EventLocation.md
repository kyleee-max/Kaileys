# Class: EventLocation

Defined in: [WAProto/index.d.ts:9740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9740)

## Implements

- [`IEventLocation`](../interfaces/IEventLocation.md)

## Constructors

### new EventLocation()

> **new EventLocation**(`p`?): [`EventLocation`](EventLocation.md)

Defined in: [WAProto/index.d.ts:9741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9741)

#### Parameters

##### p?

[`IEventLocation`](../interfaces/IEventLocation.md)

#### Returns

[`EventLocation`](EventLocation.md)

## Properties

### address?

> `optional` **address**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9745)

#### Implementation of

[`IEventLocation`](../interfaces/IEventLocation.md).[`address`](../interfaces/IEventLocation.md#address)

***

### degreesLatitude?

> `optional` **degreesLatitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9742)

#### Implementation of

[`IEventLocation`](../interfaces/IEventLocation.md).[`degreesLatitude`](../interfaces/IEventLocation.md#degreeslatitude)

***

### degreesLongitude?

> `optional` **degreesLongitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9743)

#### Implementation of

[`IEventLocation`](../interfaces/IEventLocation.md).[`degreesLongitude`](../interfaces/IEventLocation.md#degreeslongitude)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9747)

#### Implementation of

[`IEventLocation`](../interfaces/IEventLocation.md).[`jpegThumbnail`](../interfaces/IEventLocation.md#jpegthumbnail)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9744)

#### Implementation of

[`IEventLocation`](../interfaces/IEventLocation.md).[`name`](../interfaces/IEventLocation.md#name)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9746)

#### Implementation of

[`IEventLocation`](../interfaces/IEventLocation.md).[`url`](../interfaces/IEventLocation.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9753](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9753)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EventLocation`](EventLocation.md)

Defined in: [WAProto/index.d.ts:9748](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9748)

#### Parameters

##### properties?

[`IEventLocation`](../interfaces/IEventLocation.md)

#### Returns

[`EventLocation`](EventLocation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EventLocation`](EventLocation.md)

Defined in: [WAProto/index.d.ts:9750](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9750)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EventLocation`](EventLocation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9749](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9749)

#### Parameters

##### m

[`IEventLocation`](../interfaces/IEventLocation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EventLocation`](EventLocation.md)

Defined in: [WAProto/index.d.ts:9751](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9751)

#### Parameters

##### d

#### Returns

[`EventLocation`](EventLocation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9754](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9754)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9752](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9752)

#### Parameters

##### m

[`EventLocation`](EventLocation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
