# Class: FullHistorySyncOnDemandRequestResponse

Defined in: [WAProto/index.d.ts:8038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8038)

## Implements

- [`IFullHistorySyncOnDemandRequestResponse`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md)

## Constructors

### new FullHistorySyncOnDemandRequestResponse()

> **new FullHistorySyncOnDemandRequestResponse**(`p`?): [`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

Defined in: [WAProto/index.d.ts:8039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8039)

#### Parameters

##### p?

[`IFullHistorySyncOnDemandRequestResponse`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md)

#### Returns

[`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

## Properties

### requestMetadata?

> `optional` **requestMetadata**: `null` \| [`IFullHistorySyncOnDemandRequestMetadata`](../../../../../interfaces/IFullHistorySyncOnDemandRequestMetadata.md)

Defined in: [WAProto/index.d.ts:8040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8040)

#### Implementation of

[`IFullHistorySyncOnDemandRequestResponse`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md).[`requestMetadata`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md#requestmetadata)

***

### responseCode?

> `optional` **responseCode**: `null` \| [`FullHistorySyncOnDemandResponseCode`](../enumerations/FullHistorySyncOnDemandResponseCode.md)

Defined in: [WAProto/index.d.ts:8041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8041)

#### Implementation of

[`IFullHistorySyncOnDemandRequestResponse`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md).[`responseCode`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md#responsecode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8047](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8047)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

Defined in: [WAProto/index.d.ts:8042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8042)

#### Parameters

##### properties?

[`IFullHistorySyncOnDemandRequestResponse`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md)

#### Returns

[`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

Defined in: [WAProto/index.d.ts:8044](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8044)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8043](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8043)

#### Parameters

##### m

[`IFullHistorySyncOnDemandRequestResponse`](../interfaces/IFullHistorySyncOnDemandRequestResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

Defined in: [WAProto/index.d.ts:8045](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8045)

#### Parameters

##### d

#### Returns

[`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8048](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8048)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8046](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8046)

#### Parameters

##### m

[`FullHistorySyncOnDemandRequestResponse`](FullHistorySyncOnDemandRequestResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
