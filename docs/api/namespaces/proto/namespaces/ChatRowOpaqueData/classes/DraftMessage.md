# Class: DraftMessage

Defined in: [WAProto/index.d.ts:2501](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2501)

## Implements

- [`IDraftMessage`](../interfaces/IDraftMessage.md)

## Constructors

### new DraftMessage()

> **new DraftMessage**(`p`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2502](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2502)

#### Parameters

##### p?

[`IDraftMessage`](../interfaces/IDraftMessage.md)

#### Returns

[`DraftMessage`](DraftMessage.md)

## Properties

### ctwaContext?

> `optional` **ctwaContext**: `null` \| [`ICtwaContextData`](../namespaces/DraftMessage/interfaces/ICtwaContextData.md)

Defined in: [WAProto/index.d.ts:2506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2506)

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`ctwaContext`](../interfaces/IDraftMessage.md#ctwacontext)

***

### ctwaContextLinkData?

> `optional` **ctwaContextLinkData**: `null` \| [`ICtwaContextLinkData`](../namespaces/DraftMessage/interfaces/ICtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2505)

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`ctwaContextLinkData`](../interfaces/IDraftMessage.md#ctwacontextlinkdata)

***

### omittedUrl?

> `optional` **omittedUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2504)

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`omittedUrl`](../interfaces/IDraftMessage.md#omittedurl)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2503)

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`text`](../interfaces/IDraftMessage.md#text)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2507](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2507)

#### Implementation of

[`IDraftMessage`](../interfaces/IDraftMessage.md).[`timestamp`](../interfaces/IDraftMessage.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2513)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2508](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2508)

#### Parameters

##### properties?

[`IDraftMessage`](../interfaces/IDraftMessage.md)

#### Returns

[`DraftMessage`](DraftMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2510](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2510)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DraftMessage`](DraftMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2509](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2509)

#### Parameters

##### m

[`IDraftMessage`](../interfaces/IDraftMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DraftMessage`](DraftMessage.md)

Defined in: [WAProto/index.d.ts:2511](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2511)

#### Parameters

##### d

#### Returns

[`DraftMessage`](DraftMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2514](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2514)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2512](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2512)

#### Parameters

##### m

[`DraftMessage`](DraftMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
