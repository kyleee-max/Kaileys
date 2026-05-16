# Class: SenderKeyRecordStructure

Defined in: [WAProto/index.d.ts:10767](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10767)

## Implements

- [`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

## Constructors

### new SenderKeyRecordStructure()

> **new SenderKeyRecordStructure**(`p`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10768](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10768)

#### Parameters

##### p?

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

## Properties

### senderKeyStates

> **senderKeyStates**: [`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)[]

Defined in: [WAProto/index.d.ts:10769](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10769)

#### Implementation of

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md).[`senderKeyStates`](../interfaces/ISenderKeyRecordStructure.md#senderkeystates)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10775)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10770](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10770)

#### Parameters

##### properties?

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10772)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10771)

#### Parameters

##### m

[`ISenderKeyRecordStructure`](../interfaces/ISenderKeyRecordStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10773)

#### Parameters

##### d

#### Returns

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10776)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10774)

#### Parameters

##### m

[`SenderKeyRecordStructure`](SenderKeyRecordStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
