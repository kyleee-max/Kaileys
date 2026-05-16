# Class: BotMemuMetadata

Defined in: [WAProto/index.d.ts:1427](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1427)

## Implements

- [`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

## Constructors

### new BotMemuMetadata()

> **new BotMemuMetadata**(`p`?): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:1428](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1428)

#### Parameters

##### p?

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

## Properties

### faceImages

> **faceImages**: [`IBotMediaMetadata`](../interfaces/IBotMediaMetadata.md)[]

Defined in: [WAProto/index.d.ts:1429](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1429)

#### Implementation of

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md).[`faceImages`](../interfaces/IBotMemuMetadata.md#faceimages)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1435)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:1430](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1430)

#### Parameters

##### properties?

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:1432](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1432)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1431](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1431)

#### Parameters

##### m

[`IBotMemuMetadata`](../interfaces/IBotMemuMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMemuMetadata`](BotMemuMetadata.md)

Defined in: [WAProto/index.d.ts:1433](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1433)

#### Parameters

##### d

#### Returns

[`BotMemuMetadata`](BotMemuMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1436](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1436)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1434)

#### Parameters

##### m

[`BotMemuMetadata`](BotMemuMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
