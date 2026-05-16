# Class: PreKeyRecordStructure

Defined in: [WAProto/index.d.ts:10449](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10449)

## Implements

- [`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md)

## Constructors

### new PreKeyRecordStructure()

> **new PreKeyRecordStructure**(`p`?): [`PreKeyRecordStructure`](PreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10450](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10450)

#### Parameters

##### p?

[`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md)

#### Returns

[`PreKeyRecordStructure`](PreKeyRecordStructure.md)

## Properties

### id?

> `optional` **id**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10451](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10451)

#### Implementation of

[`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md).[`id`](../interfaces/IPreKeyRecordStructure.md#id)

***

### privateKey?

> `optional` **privateKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10453](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10453)

#### Implementation of

[`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md).[`privateKey`](../interfaces/IPreKeyRecordStructure.md#privatekey)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10452](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10452)

#### Implementation of

[`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md).[`publicKey`](../interfaces/IPreKeyRecordStructure.md#publickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10459)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PreKeyRecordStructure`](PreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10454](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10454)

#### Parameters

##### properties?

[`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md)

#### Returns

[`PreKeyRecordStructure`](PreKeyRecordStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PreKeyRecordStructure`](PreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10456)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PreKeyRecordStructure`](PreKeyRecordStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10455](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10455)

#### Parameters

##### m

[`IPreKeyRecordStructure`](../interfaces/IPreKeyRecordStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PreKeyRecordStructure`](PreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:10457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10457)

#### Parameters

##### d

#### Returns

[`PreKeyRecordStructure`](PreKeyRecordStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10460)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10458)

#### Parameters

##### m

[`PreKeyRecordStructure`](PreKeyRecordStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
