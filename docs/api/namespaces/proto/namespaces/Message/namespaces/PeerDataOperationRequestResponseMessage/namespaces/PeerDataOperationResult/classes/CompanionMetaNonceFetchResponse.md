# Class: CompanionMetaNonceFetchResponse

Defined in: [WAProto/index.d.ts:8021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8021)

## Implements

- [`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

## Constructors

### new CompanionMetaNonceFetchResponse()

> **new CompanionMetaNonceFetchResponse**(`p`?): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8022)

#### Parameters

##### p?

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

## Properties

### nonce?

> `optional` **nonce**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8023)

#### Implementation of

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md).[`nonce`](../interfaces/ICompanionMetaNonceFetchResponse.md#nonce)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8029](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8029)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8024)

#### Parameters

##### properties?

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8026](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8026)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8025)

#### Parameters

##### m

[`ICompanionMetaNonceFetchResponse`](../interfaces/ICompanionMetaNonceFetchResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8027](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8027)

#### Parameters

##### d

#### Returns

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8030](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8030)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8028](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8028)

#### Parameters

##### m

[`CompanionMetaNonceFetchResponse`](CompanionMetaNonceFetchResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
