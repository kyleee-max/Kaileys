# Class: ADVSignedKeyIndexList

Defined in: [WAProto/index.d.ts:106](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L106)

## Implements

- [`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

## Constructors

### new ADVSignedKeyIndexList()

> **new ADVSignedKeyIndexList**(`p`?): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L107)

#### Parameters

##### p?

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

## Properties

### accountSignature?

> `optional` **accountSignature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:109](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L109)

#### Implementation of

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md).[`accountSignature`](../interfaces/IADVSignedKeyIndexList.md#accountsignature)

***

### accountSignatureKey?

> `optional` **accountSignatureKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:110](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L110)

#### Implementation of

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md).[`accountSignatureKey`](../interfaces/IADVSignedKeyIndexList.md#accountsignaturekey)

***

### details?

> `optional` **details**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:108](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L108)

#### Implementation of

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md).[`details`](../interfaces/IADVSignedKeyIndexList.md#details)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L116)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:111](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L111)

#### Parameters

##### properties?

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:113](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L113)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:112](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L112)

#### Parameters

##### m

[`IADVSignedKeyIndexList`](../interfaces/IADVSignedKeyIndexList.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

Defined in: [WAProto/index.d.ts:114](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L114)

#### Parameters

##### d

#### Returns

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L117)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:115](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L115)

#### Parameters

##### m

[`ADVSignedKeyIndexList`](ADVSignedKeyIndexList.md)

##### o?

`IConversionOptions`

#### Returns

`object`
