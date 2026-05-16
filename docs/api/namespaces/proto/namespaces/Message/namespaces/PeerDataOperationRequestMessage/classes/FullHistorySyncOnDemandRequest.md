# Class: FullHistorySyncOnDemandRequest

Defined in: [WAProto/index.d.ts:7782](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7782)

## Implements

- [`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

## Constructors

### new FullHistorySyncOnDemandRequest()

> **new FullHistorySyncOnDemandRequest**(`p`?): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7783](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7783)

#### Parameters

##### p?

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

## Properties

### historySyncConfig?

> `optional` **historySyncConfig**: `null` \| [`IHistorySyncConfig`](../../../../DeviceProps/interfaces/IHistorySyncConfig.md)

Defined in: [WAProto/index.d.ts:7785](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7785)

#### Implementation of

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md).[`historySyncConfig`](../interfaces/IFullHistorySyncOnDemandRequest.md#historysyncconfig)

***

### requestMetadata?

> `optional` **requestMetadata**: `null` \| [`IFullHistorySyncOnDemandRequestMetadata`](../../../interfaces/IFullHistorySyncOnDemandRequestMetadata.md)

Defined in: [WAProto/index.d.ts:7784](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7784)

#### Implementation of

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md).[`requestMetadata`](../interfaces/IFullHistorySyncOnDemandRequest.md#requestmetadata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7791)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7786](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7786)

#### Parameters

##### properties?

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7788](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7788)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7787](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7787)

#### Parameters

##### m

[`IFullHistorySyncOnDemandRequest`](../interfaces/IFullHistorySyncOnDemandRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

Defined in: [WAProto/index.d.ts:7789](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7789)

#### Parameters

##### d

#### Returns

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7792)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7790](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7790)

#### Parameters

##### m

[`FullHistorySyncOnDemandRequest`](FullHistorySyncOnDemandRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
