# Class: DataSharingContext

Defined in: [WAProto/index.d.ts:3309](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3309)

## Implements

- [`IDataSharingContext`](../interfaces/IDataSharingContext.md)

## Constructors

### new DataSharingContext()

> **new DataSharingContext**(`p`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:3310](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3310)

#### Parameters

##### p?

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

#### Returns

[`DataSharingContext`](DataSharingContext.md)

## Properties

### dataSharingFlags?

> `optional` **dataSharingFlags**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3314](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3314)

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`dataSharingFlags`](../interfaces/IDataSharingContext.md#datasharingflags)

***

### encryptedSignalTokenConsented?

> `optional` **encryptedSignalTokenConsented**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3312](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3312)

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`encryptedSignalTokenConsented`](../interfaces/IDataSharingContext.md#encryptedsignaltokenconsented)

***

### parameters

> **parameters**: [`IParameters`](../namespaces/DataSharingContext/interfaces/IParameters.md)[]

Defined in: [WAProto/index.d.ts:3313](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3313)

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`parameters`](../interfaces/IDataSharingContext.md#parameters)

***

### showMmDisclosure?

> `optional` **showMmDisclosure**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3311](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3311)

#### Implementation of

[`IDataSharingContext`](../interfaces/IDataSharingContext.md).[`showMmDisclosure`](../interfaces/IDataSharingContext.md#showmmdisclosure)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3320)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:3315](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3315)

#### Parameters

##### properties?

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

#### Returns

[`DataSharingContext`](DataSharingContext.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:3317](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3317)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DataSharingContext`](DataSharingContext.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3316](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3316)

#### Parameters

##### m

[`IDataSharingContext`](../interfaces/IDataSharingContext.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DataSharingContext`](DataSharingContext.md)

Defined in: [WAProto/index.d.ts:3318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3318)

#### Parameters

##### d

#### Returns

[`DataSharingContext`](DataSharingContext.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3321](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3321)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3319](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3319)

#### Parameters

##### m

[`DataSharingContext`](DataSharingContext.md)

##### o?

`IConversionOptions`

#### Returns

`object`
