# Class: WaffleNonceFetchResponse

Defined in: [WAProto/index.d.ts:8212](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8212)

## Implements

- [`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

## Constructors

### new WaffleNonceFetchResponse()

> **new WaffleNonceFetchResponse**(`p`?): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8213](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8213)

#### Parameters

##### p?

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

## Properties

### nonce?

> `optional` **nonce**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8214](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8214)

#### Implementation of

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md).[`nonce`](../interfaces/IWaffleNonceFetchResponse.md#nonce)

***

### waEntFbid?

> `optional` **waEntFbid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8215](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8215)

#### Implementation of

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md).[`waEntFbid`](../interfaces/IWaffleNonceFetchResponse.md#waentfbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8221](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8221)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8216](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8216)

#### Parameters

##### properties?

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8218](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8218)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8217](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8217)

#### Parameters

##### m

[`IWaffleNonceFetchResponse`](../interfaces/IWaffleNonceFetchResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

Defined in: [WAProto/index.d.ts:8219](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8219)

#### Parameters

##### d

#### Returns

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8222)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8220](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8220)

#### Parameters

##### m

[`WaffleNonceFetchResponse`](WaffleNonceFetchResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
