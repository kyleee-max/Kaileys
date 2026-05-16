# Class: CollectionMessage

Defined in: [WAProto/index.d.ts:6818](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6818)

## Implements

- [`ICollectionMessage`](../interfaces/ICollectionMessage.md)

## Constructors

### new CollectionMessage()

> **new CollectionMessage**(`p`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:6819](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6819)

#### Parameters

##### p?

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

#### Returns

[`CollectionMessage`](CollectionMessage.md)

## Properties

### bizJid?

> `optional` **bizJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6820](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6820)

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`bizJid`](../interfaces/ICollectionMessage.md#bizjid)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6821](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6821)

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`id`](../interfaces/ICollectionMessage.md#id)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6822](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6822)

#### Implementation of

[`ICollectionMessage`](../interfaces/ICollectionMessage.md).[`messageVersion`](../interfaces/ICollectionMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6828)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:6823](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6823)

#### Parameters

##### properties?

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

#### Returns

[`CollectionMessage`](CollectionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:6825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6825)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CollectionMessage`](CollectionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6824)

#### Parameters

##### m

[`ICollectionMessage`](../interfaces/ICollectionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CollectionMessage`](CollectionMessage.md)

Defined in: [WAProto/index.d.ts:6826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6826)

#### Parameters

##### d

#### Returns

[`CollectionMessage`](CollectionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6829)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6827)

#### Parameters

##### m

[`CollectionMessage`](CollectionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
