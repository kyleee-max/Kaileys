# Class: GroupHistoryBundleInfo

Defined in: [WAProto/index.d.ts:4339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4339)

## Implements

- [`IGroupHistoryBundleInfo`](../interfaces/IGroupHistoryBundleInfo.md)

## Constructors

### new GroupHistoryBundleInfo()

> **new GroupHistoryBundleInfo**(`p`?): [`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

Defined in: [WAProto/index.d.ts:4340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4340)

#### Parameters

##### p?

[`IGroupHistoryBundleInfo`](../interfaces/IGroupHistoryBundleInfo.md)

#### Returns

[`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

## Properties

### deprecatedMessageHistoryBundle?

> `optional` **deprecatedMessageHistoryBundle**: `null` \| [`IMessageHistoryBundle`](../namespaces/Message/interfaces/IMessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:4341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4341)

#### Implementation of

[`IGroupHistoryBundleInfo`](../interfaces/IGroupHistoryBundleInfo.md).[`deprecatedMessageHistoryBundle`](../interfaces/IGroupHistoryBundleInfo.md#deprecatedmessagehistorybundle)

***

### processState?

> `optional` **processState**: `null` \| [`ProcessState`](../namespaces/GroupHistoryBundleInfo/enumerations/ProcessState.md)

Defined in: [WAProto/index.d.ts:4342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4342)

#### Implementation of

[`IGroupHistoryBundleInfo`](../interfaces/IGroupHistoryBundleInfo.md).[`processState`](../interfaces/IGroupHistoryBundleInfo.md#processstate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4348)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

Defined in: [WAProto/index.d.ts:4343](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4343)

#### Parameters

##### properties?

[`IGroupHistoryBundleInfo`](../interfaces/IGroupHistoryBundleInfo.md)

#### Returns

[`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

Defined in: [WAProto/index.d.ts:4345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4345)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4344)

#### Parameters

##### m

[`IGroupHistoryBundleInfo`](../interfaces/IGroupHistoryBundleInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

Defined in: [WAProto/index.d.ts:4346](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4346)

#### Parameters

##### d

#### Returns

[`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4349)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4347)

#### Parameters

##### m

[`GroupHistoryBundleInfo`](GroupHistoryBundleInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
