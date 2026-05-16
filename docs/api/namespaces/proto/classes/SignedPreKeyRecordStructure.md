# Class: SignedPreKeyRecordStructure

Defined in: [WAProto/index.d.ts:11085](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11085)

## Implements

- [`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

## Constructors

### new SignedPreKeyRecordStructure()

> **new SignedPreKeyRecordStructure**(`p`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:11086](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11086)

#### Parameters

##### p?

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

## Properties

### id?

> `optional` **id**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11087](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11087)

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`id`](../interfaces/ISignedPreKeyRecordStructure.md#id)

***

### privateKey?

> `optional` **privateKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11089](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11089)

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`privateKey`](../interfaces/ISignedPreKeyRecordStructure.md#privatekey)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11088](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11088)

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`publicKey`](../interfaces/ISignedPreKeyRecordStructure.md#publickey)

***

### signature?

> `optional` **signature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11090](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11090)

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`signature`](../interfaces/ISignedPreKeyRecordStructure.md#signature)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:11091](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11091)

#### Implementation of

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md).[`timestamp`](../interfaces/ISignedPreKeyRecordStructure.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11097)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:11092](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11092)

#### Parameters

##### properties?

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:11094](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11094)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11093](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11093)

#### Parameters

##### m

[`ISignedPreKeyRecordStructure`](../interfaces/ISignedPreKeyRecordStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

Defined in: [WAProto/index.d.ts:11095](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11095)

#### Parameters

##### d

#### Returns

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11098](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11098)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11096](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11096)

#### Parameters

##### m

[`SignedPreKeyRecordStructure`](SignedPreKeyRecordStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
