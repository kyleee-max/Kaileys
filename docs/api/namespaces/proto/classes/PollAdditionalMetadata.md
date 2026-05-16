# Class: PollAdditionalMetadata

Defined in: [WAProto/index.d.ts:10389](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10389)

## Implements

- [`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

## Constructors

### new PollAdditionalMetadata()

> **new PollAdditionalMetadata**(`p`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:10390](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10390)

#### Parameters

##### p?

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

## Properties

### pollInvalidated?

> `optional` **pollInvalidated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:10391](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10391)

#### Implementation of

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md).[`pollInvalidated`](../interfaces/IPollAdditionalMetadata.md#pollinvalidated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10397](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10397)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:10392](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10392)

#### Parameters

##### properties?

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:10394](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10394)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10393](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10393)

#### Parameters

##### m

[`IPollAdditionalMetadata`](../interfaces/IPollAdditionalMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollAdditionalMetadata`](PollAdditionalMetadata.md)

Defined in: [WAProto/index.d.ts:10395](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10395)

#### Parameters

##### d

#### Returns

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10398](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10398)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10396](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10396)

#### Parameters

##### m

[`PollAdditionalMetadata`](PollAdditionalMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
