# Class: BotMessageSharingInfo

Defined in: [WAProto/index.d.ts:1483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1483)

## Implements

- [`IBotMessageSharingInfo`](../interfaces/IBotMessageSharingInfo.md)

## Constructors

### new BotMessageSharingInfo()

> **new BotMessageSharingInfo**(`p`?): [`BotMessageSharingInfo`](BotMessageSharingInfo.md)

Defined in: [WAProto/index.d.ts:1484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1484)

#### Parameters

##### p?

[`IBotMessageSharingInfo`](../interfaces/IBotMessageSharingInfo.md)

#### Returns

[`BotMessageSharingInfo`](BotMessageSharingInfo.md)

## Properties

### botEntryPointOrigin?

> `optional` **botEntryPointOrigin**: `null` \| [`BotMetricsEntryPoint`](../enumerations/BotMetricsEntryPoint.md)

Defined in: [WAProto/index.d.ts:1485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1485)

#### Implementation of

[`IBotMessageSharingInfo`](../interfaces/IBotMessageSharingInfo.md).[`botEntryPointOrigin`](../interfaces/IBotMessageSharingInfo.md#botentrypointorigin)

***

### forwardScore?

> `optional` **forwardScore**: `null` \| `number`

Defined in: [WAProto/index.d.ts:1486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1486)

#### Implementation of

[`IBotMessageSharingInfo`](../interfaces/IBotMessageSharingInfo.md).[`forwardScore`](../interfaces/IBotMessageSharingInfo.md#forwardscore)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1492](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1492)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMessageSharingInfo`](BotMessageSharingInfo.md)

Defined in: [WAProto/index.d.ts:1487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1487)

#### Parameters

##### properties?

[`IBotMessageSharingInfo`](../interfaces/IBotMessageSharingInfo.md)

#### Returns

[`BotMessageSharingInfo`](BotMessageSharingInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMessageSharingInfo`](BotMessageSharingInfo.md)

Defined in: [WAProto/index.d.ts:1489](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1489)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMessageSharingInfo`](BotMessageSharingInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1488)

#### Parameters

##### m

[`IBotMessageSharingInfo`](../interfaces/IBotMessageSharingInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMessageSharingInfo`](BotMessageSharingInfo.md)

Defined in: [WAProto/index.d.ts:1490](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1490)

#### Parameters

##### d

#### Returns

[`BotMessageSharingInfo`](BotMessageSharingInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1493](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1493)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1491](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1491)

#### Parameters

##### m

[`BotMessageSharingInfo`](BotMessageSharingInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
