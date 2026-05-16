# Class: BotImagineMetadata

Defined in: [WAProto/index.d.ts:1282](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1282)

## Implements

- [`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

## Constructors

### new BotImagineMetadata()

> **new BotImagineMetadata**(`p`?): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:1283](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1283)

#### Parameters

##### p?

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

## Properties

### imagineType?

> `optional` **imagineType**: `null` \| [`ImagineType`](../namespaces/BotImagineMetadata/enumerations/ImagineType.md)

Defined in: [WAProto/index.d.ts:1284](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1284)

#### Implementation of

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md).[`imagineType`](../interfaces/IBotImagineMetadata.md#imaginetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1290](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1290)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:1285](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1285)

#### Parameters

##### properties?

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:1287](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1287)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1286](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1286)

#### Parameters

##### m

[`IBotImagineMetadata`](../interfaces/IBotImagineMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotImagineMetadata`](BotImagineMetadata.md)

Defined in: [WAProto/index.d.ts:1288](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1288)

#### Parameters

##### d

#### Returns

[`BotImagineMetadata`](BotImagineMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1291)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1289](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1289)

#### Parameters

##### m

[`BotImagineMetadata`](BotImagineMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
