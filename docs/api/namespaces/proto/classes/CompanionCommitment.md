# Class: CompanionCommitment

Defined in: [WAProto/index.d.ts:3079](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3079)

## Implements

- [`ICompanionCommitment`](../interfaces/ICompanionCommitment.md)

## Constructors

### new CompanionCommitment()

> **new CompanionCommitment**(`p`?): [`CompanionCommitment`](CompanionCommitment.md)

Defined in: [WAProto/index.d.ts:3080](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3080)

#### Parameters

##### p?

[`ICompanionCommitment`](../interfaces/ICompanionCommitment.md)

#### Returns

[`CompanionCommitment`](CompanionCommitment.md)

## Properties

### hash?

> `optional` **hash**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3081](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3081)

#### Implementation of

[`ICompanionCommitment`](../interfaces/ICompanionCommitment.md).[`hash`](../interfaces/ICompanionCommitment.md#hash)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3087](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3087)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CompanionCommitment`](CompanionCommitment.md)

Defined in: [WAProto/index.d.ts:3082](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3082)

#### Parameters

##### properties?

[`ICompanionCommitment`](../interfaces/ICompanionCommitment.md)

#### Returns

[`CompanionCommitment`](CompanionCommitment.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CompanionCommitment`](CompanionCommitment.md)

Defined in: [WAProto/index.d.ts:3084](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3084)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CompanionCommitment`](CompanionCommitment.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3083](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3083)

#### Parameters

##### m

[`ICompanionCommitment`](../interfaces/ICompanionCommitment.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CompanionCommitment`](CompanionCommitment.md)

Defined in: [WAProto/index.d.ts:3085](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3085)

#### Parameters

##### d

#### Returns

[`CompanionCommitment`](CompanionCommitment.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3088](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3088)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3086](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3086)

#### Parameters

##### m

[`CompanionCommitment`](CompanionCommitment.md)

##### o?

`IConversionOptions`

#### Returns

`object`
