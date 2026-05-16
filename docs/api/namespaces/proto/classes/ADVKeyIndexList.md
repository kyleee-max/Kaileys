# Class: ADVKeyIndexList

Defined in: [WAProto/index.d.ts:42](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L42)

## Implements

- [`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

## Constructors

### new ADVKeyIndexList()

> **new ADVKeyIndexList**(`p`?): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:43](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L43)

#### Parameters

##### p?

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

## Properties

### accountType?

> `optional` **accountType**: `null` \| [`ADVEncryptionType`](../enumerations/ADVEncryptionType.md)

Defined in: [WAProto/index.d.ts:48](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L48)

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`accountType`](../interfaces/IADVKeyIndexList.md#accounttype)

***

### currentIndex?

> `optional` **currentIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:46](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L46)

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`currentIndex`](../interfaces/IADVKeyIndexList.md#currentindex)

***

### rawId?

> `optional` **rawId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:44](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L44)

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`rawId`](../interfaces/IADVKeyIndexList.md#rawid)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:45](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L45)

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`timestamp`](../interfaces/IADVKeyIndexList.md#timestamp)

***

### validIndexes

> **validIndexes**: `number`[]

Defined in: [WAProto/index.d.ts:47](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L47)

#### Implementation of

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md).[`validIndexes`](../interfaces/IADVKeyIndexList.md#validindexes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:54](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L54)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:49](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L49)

#### Parameters

##### properties?

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:51](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L51)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:50](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L50)

#### Parameters

##### m

[`IADVKeyIndexList`](../interfaces/IADVKeyIndexList.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ADVKeyIndexList`](ADVKeyIndexList.md)

Defined in: [WAProto/index.d.ts:52](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L52)

#### Parameters

##### d

#### Returns

[`ADVKeyIndexList`](ADVKeyIndexList.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:55](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L55)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:53](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L53)

#### Parameters

##### m

[`ADVKeyIndexList`](ADVKeyIndexList.md)

##### o?

`IConversionOptions`

#### Returns

`object`
