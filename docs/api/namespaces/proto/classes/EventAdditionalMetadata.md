# Class: EventAdditionalMetadata

Defined in: [WAProto/index.d.ts:4158](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4158)

## Implements

- [`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

## Constructors

### new EventAdditionalMetadata()

> **new EventAdditionalMetadata**(`p`?): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:4159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4159)

#### Parameters

##### p?

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

## Properties

### isStale?

> `optional` **isStale**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4160](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4160)

#### Implementation of

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md).[`isStale`](../interfaces/IEventAdditionalMetadata.md#isstale)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4166)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:4161](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4161)

#### Parameters

##### properties?

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:4163](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4163)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4162](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4162)

#### Parameters

##### m

[`IEventAdditionalMetadata`](../interfaces/IEventAdditionalMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EventAdditionalMetadata`](EventAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:4164](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4164)

#### Parameters

##### d

#### Returns

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4167)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4165)

#### Parameters

##### m

[`EventAdditionalMetadata`](EventAdditionalMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
