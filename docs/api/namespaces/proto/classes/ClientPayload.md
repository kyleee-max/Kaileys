# Class: ClientPayload

Defined in: [WAProto/index.d.ts:2669](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2669)

## Implements

- [`IClientPayload`](../interfaces/IClientPayload.md)

## Constructors

### new ClientPayload()

> **new ClientPayload**(`p`?): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:2670](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2670)

#### Parameters

##### p?

[`IClientPayload`](../interfaces/IClientPayload.md)

#### Returns

[`ClientPayload`](ClientPayload.md)

## Properties

### accountType?

> `optional` **accountType**: `null` \| [`AccountType`](../namespaces/ClientPayload/enumerations/AccountType.md)

Defined in: [WAProto/index.d.ts:2700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2700)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`accountType`](../interfaces/IClientPayload.md#accounttype)

***

### connectAttemptCount?

> `optional` **connectAttemptCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2682)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectAttemptCount`](../interfaces/IClientPayload.md#connectattemptcount)

***

### connectionSequenceInfo?

> `optional` **connectionSequenceInfo**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2701](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2701)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectionSequenceInfo`](../interfaces/IClientPayload.md#connectionsequenceinfo)

***

### connectReason?

> `optional` **connectReason**: `null` \| [`ConnectReason`](../namespaces/ClientPayload/enumerations/ConnectReason.md)

Defined in: [WAProto/index.d.ts:2679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2679)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectReason`](../interfaces/IClientPayload.md#connectreason)

***

### connectType?

> `optional` **connectType**: `null` \| [`ConnectType`](../namespaces/ClientPayload/enumerations/ConnectType.md)

Defined in: [WAProto/index.d.ts:2678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2678)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`connectType`](../interfaces/IClientPayload.md#connecttype)

***

### device?

> `optional` **device**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2683](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2683)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`device`](../interfaces/IClientPayload.md#device)

***

### devicePairingData?

> `optional` **devicePairingData**: `null` \| [`IDevicePairingRegistrationData`](../namespaces/ClientPayload/interfaces/IDevicePairingRegistrationData.md)

Defined in: [WAProto/index.d.ts:2684](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2684)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`devicePairingData`](../interfaces/IClientPayload.md#devicepairingdata)

***

### dnsSource?

> `optional` **dnsSource**: `null` \| [`IDNSSource`](../namespaces/ClientPayload/interfaces/IDNSSource.md)

Defined in: [WAProto/index.d.ts:2681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2681)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`dnsSource`](../interfaces/IClientPayload.md#dnssource)

***

### fbAppId?

> `optional` **fbAppId**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2691](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2691)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbAppId`](../interfaces/IClientPayload.md#fbappid)

***

### fbCat?

> `optional` **fbCat**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2686](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2686)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbCat`](../interfaces/IClientPayload.md#fbcat)

***

### fbDeviceId?

> `optional` **fbDeviceId**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2692](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2692)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbDeviceId`](../interfaces/IClientPayload.md#fbdeviceid)

***

### fbUserAgent?

> `optional` **fbUserAgent**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2687](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2687)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`fbUserAgent`](../interfaces/IClientPayload.md#fbuseragent)

***

### interopData?

> `optional` **interopData**: `null` \| [`IInteropData`](../namespaces/ClientPayload/interfaces/IInteropData.md)

Defined in: [WAProto/index.d.ts:2697](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2697)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`interopData`](../interfaces/IClientPayload.md#interopdata)

***

### iosAppExtension?

> `optional` **iosAppExtension**: `null` \| [`IOSAppExtension`](../namespaces/ClientPayload/enumerations/IOSAppExtension.md)

Defined in: [WAProto/index.d.ts:2690](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2690)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`iosAppExtension`](../interfaces/IClientPayload.md#iosappextension)

***

### lc?

> `optional` **lc**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2689](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2689)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`lc`](../interfaces/IClientPayload.md#lc)

***

### lidDbMigrated?

> `optional` **lidDbMigrated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2699)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`lidDbMigrated`](../interfaces/IClientPayload.md#liddbmigrated)

***

### memClass?

> `optional` **memClass**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2696](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2696)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`memClass`](../interfaces/IClientPayload.md#memclass)

***

### oc?

> `optional` **oc**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2688](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2688)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`oc`](../interfaces/IClientPayload.md#oc)

***

### paaLink?

> `optional` **paaLink**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2702](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2702)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`paaLink`](../interfaces/IClientPayload.md#paalink)

***

### paddingBytes?

> `optional` **paddingBytes**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2694](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2694)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`paddingBytes`](../interfaces/IClientPayload.md#paddingbytes)

***

### passive?

> `optional` **passive**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2672](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2672)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`passive`](../interfaces/IClientPayload.md#passive)

***

### preacksCount?

> `optional` **preacksCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2703](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2703)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`preacksCount`](../interfaces/IClientPayload.md#preackscount)

***

### processingQueueSize?

> `optional` **processingQueueSize**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2704](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2704)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`processingQueueSize`](../interfaces/IClientPayload.md#processingqueuesize)

***

### product?

> `optional` **product**: `null` \| [`Product`](../namespaces/ClientPayload/enumerations/Product.md)

Defined in: [WAProto/index.d.ts:2685](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2685)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`product`](../interfaces/IClientPayload.md#product)

***

### pull?

> `optional` **pull**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2693](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2693)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`pull`](../interfaces/IClientPayload.md#pull)

***

### pushName?

> `optional` **pushName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2675)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`pushName`](../interfaces/IClientPayload.md#pushname)

***

### sessionId?

> `optional` **sessionId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2676)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`sessionId`](../interfaces/IClientPayload.md#sessionid)

***

### shards

> **shards**: `number`[]

Defined in: [WAProto/index.d.ts:2680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2680)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`shards`](../interfaces/IClientPayload.md#shards)

***

### shortConnect?

> `optional` **shortConnect**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2677)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`shortConnect`](../interfaces/IClientPayload.md#shortconnect)

***

### trafficAnonymization?

> `optional` **trafficAnonymization**: `null` \| [`TrafficAnonymization`](../namespaces/ClientPayload/enumerations/TrafficAnonymization.md)

Defined in: [WAProto/index.d.ts:2698](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2698)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`trafficAnonymization`](../interfaces/IClientPayload.md#trafficanonymization)

***

### userAgent?

> `optional` **userAgent**: `null` \| [`IUserAgent`](../namespaces/ClientPayload/interfaces/IUserAgent.md)

Defined in: [WAProto/index.d.ts:2673](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2673)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`userAgent`](../interfaces/IClientPayload.md#useragent)

***

### username?

> `optional` **username**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2671](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2671)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`username`](../interfaces/IClientPayload.md#username)

***

### webInfo?

> `optional` **webInfo**: `null` \| [`IWebInfo`](../namespaces/ClientPayload/interfaces/IWebInfo.md)

Defined in: [WAProto/index.d.ts:2674](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2674)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`webInfo`](../interfaces/IClientPayload.md#webinfo)

***

### yearClass?

> `optional` **yearClass**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2695](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2695)

#### Implementation of

[`IClientPayload`](../interfaces/IClientPayload.md).[`yearClass`](../interfaces/IClientPayload.md#yearclass)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2710](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2710)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:2705](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2705)

#### Parameters

##### properties?

[`IClientPayload`](../interfaces/IClientPayload.md)

#### Returns

[`ClientPayload`](ClientPayload.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:2707](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2707)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ClientPayload`](ClientPayload.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2706)

#### Parameters

##### m

[`IClientPayload`](../interfaces/IClientPayload.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ClientPayload`](ClientPayload.md)

Defined in: [WAProto/index.d.ts:2708](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2708)

#### Parameters

##### d

#### Returns

[`ClientPayload`](ClientPayload.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2711](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2711)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2709)

#### Parameters

##### m

[`ClientPayload`](ClientPayload.md)

##### o?

`IConversionOptions`

#### Returns

`object`
