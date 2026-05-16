# Class: BotRenderingMetadata

Defined in: [WAProto/index.d.ts:2053](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2053)

## Implements

- [`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

## Constructors

### new BotRenderingMetadata()

> **new BotRenderingMetadata**(`p`?): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:2054](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2054)

#### Parameters

##### p?

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

## Properties

### keywords

> **keywords**: [`IKeyword`](../namespaces/BotRenderingMetadata/interfaces/IKeyword.md)[]

Defined in: [WAProto/index.d.ts:2055](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2055)

#### Implementation of

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md).[`keywords`](../interfaces/IBotRenderingMetadata.md#keywords)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2061](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2061)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:2056](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2056)

#### Parameters

##### properties?

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:2058](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2058)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2057](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2057)

#### Parameters

##### m

[`IBotRenderingMetadata`](../interfaces/IBotRenderingMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotRenderingMetadata`](BotRenderingMetadata.md)

Defined in: [WAProto/index.d.ts:2059](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2059)

#### Parameters

##### d

#### Returns

[`BotRenderingMetadata`](BotRenderingMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2062)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2060](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2060)

#### Parameters

##### m

[`BotRenderingMetadata`](BotRenderingMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
