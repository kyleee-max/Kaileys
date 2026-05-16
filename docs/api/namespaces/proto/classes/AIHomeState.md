# Class: AIHomeState

Defined in: [WAProto/index.d.ts:126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L126)

## Implements

- [`IAIHomeState`](../interfaces/IAIHomeState.md)

## Constructors

### new AIHomeState()

> **new AIHomeState**(`p`?): [`AIHomeState`](AIHomeState.md)

Defined in: [WAProto/index.d.ts:127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L127)

#### Parameters

##### p?

[`IAIHomeState`](../interfaces/IAIHomeState.md)

#### Returns

[`AIHomeState`](AIHomeState.md)

## Properties

### capabilityOptions

> **capabilityOptions**: [`IAIHomeOption`](../namespaces/AIHomeState/interfaces/IAIHomeOption.md)[]

Defined in: [WAProto/index.d.ts:129](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L129)

#### Implementation of

[`IAIHomeState`](../interfaces/IAIHomeState.md).[`capabilityOptions`](../interfaces/IAIHomeState.md#capabilityoptions)

***

### conversationOptions

> **conversationOptions**: [`IAIHomeOption`](../namespaces/AIHomeState/interfaces/IAIHomeOption.md)[]

Defined in: [WAProto/index.d.ts:130](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L130)

#### Implementation of

[`IAIHomeState`](../interfaces/IAIHomeState.md).[`conversationOptions`](../interfaces/IAIHomeState.md#conversationoptions)

***

### lastFetchTime?

> `optional` **lastFetchTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:128](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L128)

#### Implementation of

[`IAIHomeState`](../interfaces/IAIHomeState.md).[`lastFetchTime`](../interfaces/IAIHomeState.md#lastfetchtime)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:136](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L136)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIHomeState`](AIHomeState.md)

Defined in: [WAProto/index.d.ts:131](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L131)

#### Parameters

##### properties?

[`IAIHomeState`](../interfaces/IAIHomeState.md)

#### Returns

[`AIHomeState`](AIHomeState.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIHomeState`](AIHomeState.md)

Defined in: [WAProto/index.d.ts:133](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L133)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIHomeState`](AIHomeState.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:132](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L132)

#### Parameters

##### m

[`IAIHomeState`](../interfaces/IAIHomeState.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIHomeState`](AIHomeState.md)

Defined in: [WAProto/index.d.ts:134](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L134)

#### Parameters

##### d

#### Returns

[`AIHomeState`](AIHomeState.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:137](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L137)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:135](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L135)

#### Parameters

##### m

[`AIHomeState`](AIHomeState.md)

##### o?

`IConversionOptions`

#### Returns

`object`
