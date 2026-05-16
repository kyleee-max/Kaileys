# Class: ForwardedAIBotMessageInfo

Defined in: [WAProto/index.d.ts:4266](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4266)

## Implements

- [`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

## Constructors

### new ForwardedAIBotMessageInfo()

> **new ForwardedAIBotMessageInfo**(`p`?): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:4267](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4267)

#### Parameters

##### p?

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

## Properties

### botJid?

> `optional` **botJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4269](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4269)

#### Implementation of

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md).[`botJid`](../interfaces/IForwardedAIBotMessageInfo.md#botjid)

***

### botName?

> `optional` **botName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4268](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4268)

#### Implementation of

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md).[`botName`](../interfaces/IForwardedAIBotMessageInfo.md#botname)

***

### creatorName?

> `optional` **creatorName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4270](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4270)

#### Implementation of

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md).[`creatorName`](../interfaces/IForwardedAIBotMessageInfo.md#creatorname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4276](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4276)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:4271](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4271)

#### Parameters

##### properties?

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:4273](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4273)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4272)

#### Parameters

##### m

[`IForwardedAIBotMessageInfo`](../interfaces/IForwardedAIBotMessageInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

Defined in: [WAProto/index.d.ts:4274](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4274)

#### Parameters

##### d

#### Returns

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4277](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4277)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4275](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4275)

#### Parameters

##### m

[`ForwardedAIBotMessageInfo`](ForwardedAIBotMessageInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
