# Class: CompanionCanonicalUserNonceFetchResponse

Defined in: [WAProto/index.d.ts:8003](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8003)

## Implements

- [`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md)

## Constructors

### new CompanionCanonicalUserNonceFetchResponse()

> **new CompanionCanonicalUserNonceFetchResponse**(`p`?): [`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8004](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8004)

#### Parameters

##### p?

[`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md)

#### Returns

[`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

## Properties

### forceRefresh?

> `optional` **forceRefresh**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:8007](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8007)

#### Implementation of

[`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md).[`forceRefresh`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md#forcerefresh)

***

### nonce?

> `optional` **nonce**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8005](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8005)

#### Implementation of

[`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md).[`nonce`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md#nonce)

***

### waFbid?

> `optional` **waFbid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8006](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8006)

#### Implementation of

[`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md).[`waFbid`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md#wafbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8013](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8013)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8008](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8008)

#### Parameters

##### properties?

[`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md)

#### Returns

[`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8010](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8010)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8009](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8009)

#### Parameters

##### m

[`ICompanionCanonicalUserNonceFetchResponse`](../interfaces/ICompanionCanonicalUserNonceFetchResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8011](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8011)

#### Parameters

##### d

#### Returns

[`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8014)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8012](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8012)

#### Parameters

##### m

[`CompanionCanonicalUserNonceFetchResponse`](CompanionCanonicalUserNonceFetchResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
