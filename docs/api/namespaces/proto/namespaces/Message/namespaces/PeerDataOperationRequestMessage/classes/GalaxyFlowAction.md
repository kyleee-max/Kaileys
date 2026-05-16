# Class: GalaxyFlowAction

Defined in: [WAProto/index.d.ts:7801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7801)

## Implements

- [`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md)

## Constructors

### new GalaxyFlowAction()

> **new GalaxyFlowAction**(`p`?): [`GalaxyFlowAction`](GalaxyFlowAction.md)

Defined in: [WAProto/index.d.ts:7802](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7802)

#### Parameters

##### p?

[`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md)

#### Returns

[`GalaxyFlowAction`](GalaxyFlowAction.md)

## Properties

### flowId?

> `optional` **flowId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7804](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7804)

#### Implementation of

[`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md).[`flowId`](../interfaces/IGalaxyFlowAction.md#flowid)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7805](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7805)

#### Implementation of

[`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md).[`stanzaId`](../interfaces/IGalaxyFlowAction.md#stanzaid)

***

### type?

> `optional` **type**: `null` \| [`NOTIFY_LAUNCH`](../namespaces/GalaxyFlowAction/enumerations/GalaxyFlowActionType.md#notify_launch)

Defined in: [WAProto/index.d.ts:7803](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7803)

#### Implementation of

[`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md).[`type`](../interfaces/IGalaxyFlowAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7811)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GalaxyFlowAction`](GalaxyFlowAction.md)

Defined in: [WAProto/index.d.ts:7806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7806)

#### Parameters

##### properties?

[`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md)

#### Returns

[`GalaxyFlowAction`](GalaxyFlowAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GalaxyFlowAction`](GalaxyFlowAction.md)

Defined in: [WAProto/index.d.ts:7808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7808)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GalaxyFlowAction`](GalaxyFlowAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7807](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7807)

#### Parameters

##### m

[`IGalaxyFlowAction`](../interfaces/IGalaxyFlowAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GalaxyFlowAction`](GalaxyFlowAction.md)

Defined in: [WAProto/index.d.ts:7809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7809)

#### Parameters

##### d

#### Returns

[`GalaxyFlowAction`](GalaxyFlowAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7812](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7812)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7810)

#### Parameters

##### m

[`GalaxyFlowAction`](GalaxyFlowAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
