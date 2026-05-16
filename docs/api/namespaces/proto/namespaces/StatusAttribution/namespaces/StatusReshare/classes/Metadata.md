# Class: Metadata

Defined in: [WAProto/index.d.ts:11292](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11292)

## Implements

- [`IMetadata`](../interfaces/IMetadata.md)

## Constructors

### new Metadata()

> **new Metadata**(`p`?): [`Metadata`](Metadata.md)

Defined in: [WAProto/index.d.ts:11293](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11293)

#### Parameters

##### p?

[`IMetadata`](../interfaces/IMetadata.md)

#### Returns

[`Metadata`](Metadata.md)

## Properties

### channelJid?

> `optional` **channelJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11295](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11295)

#### Implementation of

[`IMetadata`](../interfaces/IMetadata.md).[`channelJid`](../interfaces/IMetadata.md#channeljid)

***

### channelMessageId?

> `optional` **channelMessageId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11296](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11296)

#### Implementation of

[`IMetadata`](../interfaces/IMetadata.md).[`channelMessageId`](../interfaces/IMetadata.md#channelmessageid)

***

### duration?

> `optional` **duration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11294](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11294)

#### Implementation of

[`IMetadata`](../interfaces/IMetadata.md).[`duration`](../interfaces/IMetadata.md#duration)

***

### hasMultipleReshares?

> `optional` **hasMultipleReshares**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11297](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11297)

#### Implementation of

[`IMetadata`](../interfaces/IMetadata.md).[`hasMultipleReshares`](../interfaces/IMetadata.md#hasmultiplereshares)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11303](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11303)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Metadata`](Metadata.md)

Defined in: [WAProto/index.d.ts:11298](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11298)

#### Parameters

##### properties?

[`IMetadata`](../interfaces/IMetadata.md)

#### Returns

[`Metadata`](Metadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Metadata`](Metadata.md)

Defined in: [WAProto/index.d.ts:11300](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11300)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Metadata`](Metadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11299](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11299)

#### Parameters

##### m

[`IMetadata`](../interfaces/IMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Metadata`](Metadata.md)

Defined in: [WAProto/index.d.ts:11301](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11301)

#### Parameters

##### d

#### Returns

[`Metadata`](Metadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11304](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11304)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11302](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11302)

#### Parameters

##### m

[`Metadata`](Metadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
