# Class: CtwaContextLinkData

Defined in: [WAProto/index.d.ts:2573](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2573)

## Implements

- [`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

## Constructors

### new CtwaContextLinkData()

> **new CtwaContextLinkData**(`p`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2574](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2574)

#### Parameters

##### p?

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

## Properties

### context?

> `optional` **context**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2575](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2575)

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`context`](../interfaces/ICtwaContextLinkData.md#context)

***

### icebreaker?

> `optional` **icebreaker**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2577](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2577)

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`icebreaker`](../interfaces/ICtwaContextLinkData.md#icebreaker)

***

### phone?

> `optional` **phone**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2578](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2578)

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`phone`](../interfaces/ICtwaContextLinkData.md#phone)

***

### sourceUrl?

> `optional` **sourceUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2576](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2576)

#### Implementation of

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md).[`sourceUrl`](../interfaces/ICtwaContextLinkData.md#sourceurl)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2584](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2584)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2579](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2579)

#### Parameters

##### properties?

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2581](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2581)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2580](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2580)

#### Parameters

##### m

[`ICtwaContextLinkData`](../interfaces/ICtwaContextLinkData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CtwaContextLinkData`](CtwaContextLinkData.md)

Defined in: [WAProto/index.d.ts:2582](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2582)

#### Parameters

##### d

#### Returns

[`CtwaContextLinkData`](CtwaContextLinkData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2585](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2585)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2583](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2583)

#### Parameters

##### m

[`CtwaContextLinkData`](CtwaContextLinkData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
