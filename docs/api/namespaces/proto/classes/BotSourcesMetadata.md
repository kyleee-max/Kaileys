# Class: BotSourcesMetadata

Defined in: [WAProto/index.d.ts:2164](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2164)

## Implements

- [`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

## Constructors

### new BotSourcesMetadata()

> **new BotSourcesMetadata**(`p`?): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:2165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2165)

#### Parameters

##### p?

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

## Properties

### sources

> **sources**: [`IBotSourceItem`](../namespaces/BotSourcesMetadata/interfaces/IBotSourceItem.md)[]

Defined in: [WAProto/index.d.ts:2166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2166)

#### Implementation of

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md).[`sources`](../interfaces/IBotSourcesMetadata.md#sources)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2172)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:2167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2167)

#### Parameters

##### properties?

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:2169](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2169)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2168](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2168)

#### Parameters

##### m

[`IBotSourcesMetadata`](../interfaces/IBotSourcesMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotSourcesMetadata`](BotSourcesMetadata.md)

Defined in: [WAProto/index.d.ts:2170](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2170)

#### Parameters

##### d

#### Returns

[`BotSourcesMetadata`](BotSourcesMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2173)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2171](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2171)

#### Parameters

##### m

[`BotSourcesMetadata`](BotSourcesMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
