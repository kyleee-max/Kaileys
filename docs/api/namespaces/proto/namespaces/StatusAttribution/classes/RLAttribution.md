# Class: RLAttribution

Defined in: [WAProto/index.d.ts:11243](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11243)

## Implements

- [`IRLAttribution`](../interfaces/IRLAttribution.md)

## Constructors

### new RLAttribution()

> **new RLAttribution**(`p`?): [`RLAttribution`](RLAttribution.md)

Defined in: [WAProto/index.d.ts:11244](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11244)

#### Parameters

##### p?

[`IRLAttribution`](../interfaces/IRLAttribution.md)

#### Returns

[`RLAttribution`](RLAttribution.md)

## Properties

### source?

> `optional` **source**: `null` \| [`Source`](../namespaces/RLAttribution/enumerations/Source.md)

Defined in: [WAProto/index.d.ts:11245](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11245)

#### Implementation of

[`IRLAttribution`](../interfaces/IRLAttribution.md).[`source`](../interfaces/IRLAttribution.md#source)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11251](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11251)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RLAttribution`](RLAttribution.md)

Defined in: [WAProto/index.d.ts:11246](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11246)

#### Parameters

##### properties?

[`IRLAttribution`](../interfaces/IRLAttribution.md)

#### Returns

[`RLAttribution`](RLAttribution.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RLAttribution`](RLAttribution.md)

Defined in: [WAProto/index.d.ts:11248](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11248)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RLAttribution`](RLAttribution.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11247](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11247)

#### Parameters

##### m

[`IRLAttribution`](../interfaces/IRLAttribution.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RLAttribution`](RLAttribution.md)

Defined in: [WAProto/index.d.ts:11249](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11249)

#### Parameters

##### d

#### Returns

[`RLAttribution`](RLAttribution.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11252](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11252)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11250](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11250)

#### Parameters

##### m

[`RLAttribution`](RLAttribution.md)

##### o?

`IConversionOptions`

#### Returns

`object`
