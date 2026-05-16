# Class: BotSourceItem

Defined in: [WAProto/index.d.ts:2188](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2188)

## Implements

- [`IBotSourceItem`](../interfaces/IBotSourceItem.md)

## Constructors

### new BotSourceItem()

> **new BotSourceItem**(`p`?): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:2189](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2189)

#### Parameters

##### p?

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

#### Returns

[`BotSourceItem`](BotSourceItem.md)

## Properties

### citationNumber?

> `optional` **citationNumber**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2195)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`citationNumber`](../interfaces/IBotSourceItem.md#citationnumber)

***

### faviconCdnUrl?

> `optional` **faviconCdnUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2194](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2194)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`faviconCdnUrl`](../interfaces/IBotSourceItem.md#faviconcdnurl)

***

### provider?

> `optional` **provider**: `null` \| [`SourceProvider`](../namespaces/BotSourceItem/enumerations/SourceProvider.md)

Defined in: [WAProto/index.d.ts:2190](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2190)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`provider`](../interfaces/IBotSourceItem.md#provider)

***

### sourceProviderUrl?

> `optional` **sourceProviderUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2192](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2192)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`sourceProviderUrl`](../interfaces/IBotSourceItem.md#sourceproviderurl)

***

### sourceQuery?

> `optional` **sourceQuery**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2193](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2193)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`sourceQuery`](../interfaces/IBotSourceItem.md#sourcequery)

***

### sourceTitle?

> `optional` **sourceTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2196)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`sourceTitle`](../interfaces/IBotSourceItem.md#sourcetitle)

***

### thumbnailCdnUrl?

> `optional` **thumbnailCdnUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2191](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2191)

#### Implementation of

[`IBotSourceItem`](../interfaces/IBotSourceItem.md).[`thumbnailCdnUrl`](../interfaces/IBotSourceItem.md#thumbnailcdnurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2202)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:2197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2197)

#### Parameters

##### properties?

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

#### Returns

[`BotSourceItem`](BotSourceItem.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:2199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2199)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotSourceItem`](BotSourceItem.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2198)

#### Parameters

##### m

[`IBotSourceItem`](../interfaces/IBotSourceItem.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotSourceItem`](BotSourceItem.md)

Defined in: [WAProto/index.d.ts:2200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2200)

#### Parameters

##### d

#### Returns

[`BotSourceItem`](BotSourceItem.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2203)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2201)

#### Parameters

##### m

[`BotSourceItem`](BotSourceItem.md)

##### o?

`IConversionOptions`

#### Returns

`object`
