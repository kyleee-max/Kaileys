# Class: Music

Defined in: [WAProto/index.d.ts:11222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11222)

## Implements

- [`IMusic`](../interfaces/IMusic.md)

## Constructors

### new Music()

> **new Music**(`p`?): [`Music`](Music.md)

Defined in: [WAProto/index.d.ts:11223](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11223)

#### Parameters

##### p?

[`IMusic`](../interfaces/IMusic.md)

#### Returns

[`Music`](Music.md)

## Properties

### artistAttribution?

> `optional` **artistAttribution**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11228)

#### Implementation of

[`IMusic`](../interfaces/IMusic.md).[`artistAttribution`](../interfaces/IMusic.md#artistattribution)

***

### author?

> `optional` **author**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11227](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11227)

#### Implementation of

[`IMusic`](../interfaces/IMusic.md).[`author`](../interfaces/IMusic.md#author)

***

### authorName?

> `optional` **authorName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11224](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11224)

#### Implementation of

[`IMusic`](../interfaces/IMusic.md).[`authorName`](../interfaces/IMusic.md#authorname)

***

### isExplicit?

> `optional` **isExplicit**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11229](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11229)

#### Implementation of

[`IMusic`](../interfaces/IMusic.md).[`isExplicit`](../interfaces/IMusic.md#isexplicit)

***

### songId?

> `optional` **songId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11225](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11225)

#### Implementation of

[`IMusic`](../interfaces/IMusic.md).[`songId`](../interfaces/IMusic.md#songid)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11226](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11226)

#### Implementation of

[`IMusic`](../interfaces/IMusic.md).[`title`](../interfaces/IMusic.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11235](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11235)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Music`](Music.md)

Defined in: [WAProto/index.d.ts:11230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11230)

#### Parameters

##### properties?

[`IMusic`](../interfaces/IMusic.md)

#### Returns

[`Music`](Music.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Music`](Music.md)

Defined in: [WAProto/index.d.ts:11232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11232)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Music`](Music.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11231)

#### Parameters

##### m

[`IMusic`](../interfaces/IMusic.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Music`](Music.md)

Defined in: [WAProto/index.d.ts:11233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11233)

#### Parameters

##### d

#### Returns

[`Music`](Music.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11236](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11236)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11234)

#### Parameters

##### m

[`Music`](Music.md)

##### o?

`IConversionOptions`

#### Returns

`object`
