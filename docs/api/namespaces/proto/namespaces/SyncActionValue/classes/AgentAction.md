# Class: AgentAction

Defined in: [WAProto/index.d.ts:11587](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11587)

## Implements

- [`IAgentAction`](../interfaces/IAgentAction.md)

## Constructors

### new AgentAction()

> **new AgentAction**(`p`?): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:11588](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11588)

#### Parameters

##### p?

[`IAgentAction`](../interfaces/IAgentAction.md)

#### Returns

[`AgentAction`](AgentAction.md)

## Properties

### deviceID?

> `optional` **deviceID**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11590](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11590)

#### Implementation of

[`IAgentAction`](../interfaces/IAgentAction.md).[`deviceID`](../interfaces/IAgentAction.md#deviceid)

***

### isDeleted?

> `optional` **isDeleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11591](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11591)

#### Implementation of

[`IAgentAction`](../interfaces/IAgentAction.md).[`isDeleted`](../interfaces/IAgentAction.md#isdeleted)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11589](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11589)

#### Implementation of

[`IAgentAction`](../interfaces/IAgentAction.md).[`name`](../interfaces/IAgentAction.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11597)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:11592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11592)

#### Parameters

##### properties?

[`IAgentAction`](../interfaces/IAgentAction.md)

#### Returns

[`AgentAction`](AgentAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:11594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11594)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AgentAction`](AgentAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11593)

#### Parameters

##### m

[`IAgentAction`](../interfaces/IAgentAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AgentAction`](AgentAction.md)

Defined in: [WAProto/index.d.ts:11595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11595)

#### Parameters

##### d

#### Returns

[`AgentAction`](AgentAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11598)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11596)

#### Parameters

##### m

[`AgentAction`](AgentAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
