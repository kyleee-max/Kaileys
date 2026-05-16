# Class: RecordStructure

Defined in: [WAProto/index.d.ts:10670](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10670)

## Implements

- [`IRecordStructure`](../interfaces/IRecordStructure.md)

## Constructors

### new RecordStructure()

> **new RecordStructure**(`p`?): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:10671](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10671)

#### Parameters

##### p?

[`IRecordStructure`](../interfaces/IRecordStructure.md)

#### Returns

[`RecordStructure`](RecordStructure.md)

## Properties

### currentSession?

> `optional` **currentSession**: `null` \| [`ISessionStructure`](../interfaces/ISessionStructure.md)

Defined in: [WAProto/index.d.ts:10672](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10672)

#### Implementation of

[`IRecordStructure`](../interfaces/IRecordStructure.md).[`currentSession`](../interfaces/IRecordStructure.md#currentsession)

***

### previousSessions

> **previousSessions**: [`ISessionStructure`](../interfaces/ISessionStructure.md)[]

Defined in: [WAProto/index.d.ts:10673](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10673)

#### Implementation of

[`IRecordStructure`](../interfaces/IRecordStructure.md).[`previousSessions`](../interfaces/IRecordStructure.md#previoussessions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10679)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:10674](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10674)

#### Parameters

##### properties?

[`IRecordStructure`](../interfaces/IRecordStructure.md)

#### Returns

[`RecordStructure`](RecordStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:10676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10676)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RecordStructure`](RecordStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10675)

#### Parameters

##### m

[`IRecordStructure`](../interfaces/IRecordStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RecordStructure`](RecordStructure.md)

Defined in: [WAProto/index.d.ts:10677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10677)

#### Parameters

##### d

#### Returns

[`RecordStructure`](RecordStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10680)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10678)

#### Parameters

##### m

[`RecordStructure`](RecordStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
