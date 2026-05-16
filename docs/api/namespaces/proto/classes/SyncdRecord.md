# Class: SyncdRecord

Defined in: [WAProto/index.d.ts:13086](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13086)

## Implements

- [`ISyncdRecord`](../interfaces/ISyncdRecord.md)

## Constructors

### new SyncdRecord()

> **new SyncdRecord**(`p`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:13087](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13087)

#### Parameters

##### p?

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

#### Returns

[`SyncdRecord`](SyncdRecord.md)

## Properties

### index?

> `optional` **index**: `null` \| [`ISyncdIndex`](../interfaces/ISyncdIndex.md)

Defined in: [WAProto/index.d.ts:13088](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13088)

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`index`](../interfaces/ISyncdRecord.md#index)

***

### keyId?

> `optional` **keyId**: `null` \| [`IKeyId`](../interfaces/IKeyId.md)

Defined in: [WAProto/index.d.ts:13090](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13090)

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`keyId`](../interfaces/ISyncdRecord.md#keyid)

***

### value?

> `optional` **value**: `null` \| [`ISyncdValue`](../interfaces/ISyncdValue.md)

Defined in: [WAProto/index.d.ts:13089](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13089)

#### Implementation of

[`ISyncdRecord`](../interfaces/ISyncdRecord.md).[`value`](../interfaces/ISyncdRecord.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13096](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13096)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:13091](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13091)

#### Parameters

##### properties?

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

#### Returns

[`SyncdRecord`](SyncdRecord.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:13093](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13093)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdRecord`](SyncdRecord.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13092](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13092)

#### Parameters

##### m

[`ISyncdRecord`](../interfaces/ISyncdRecord.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdRecord`](SyncdRecord.md)

Defined in: [WAProto/index.d.ts:13094](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13094)

#### Parameters

##### d

#### Returns

[`SyncdRecord`](SyncdRecord.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13097)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13095](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13095)

#### Parameters

##### m

[`SyncdRecord`](SyncdRecord.md)

##### o?

`IConversionOptions`

#### Returns

`object`
