# Class: AIThreadInfo

Defined in: [WAProto/index.d.ts:672](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L672)

## Implements

- [`IAIThreadInfo`](../interfaces/IAIThreadInfo.md)

## Constructors

### new AIThreadInfo()

> **new AIThreadInfo**(`p`?): [`AIThreadInfo`](AIThreadInfo.md)

Defined in: [WAProto/index.d.ts:673](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L673)

#### Parameters

##### p?

[`IAIThreadInfo`](../interfaces/IAIThreadInfo.md)

#### Returns

[`AIThreadInfo`](AIThreadInfo.md)

## Properties

### clientInfo?

> `optional` **clientInfo**: `null` \| [`IAIThreadClientInfo`](../namespaces/AIThreadInfo/interfaces/IAIThreadClientInfo.md)

Defined in: [WAProto/index.d.ts:675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L675)

#### Implementation of

[`IAIThreadInfo`](../interfaces/IAIThreadInfo.md).[`clientInfo`](../interfaces/IAIThreadInfo.md#clientinfo)

***

### serverInfo?

> `optional` **serverInfo**: `null` \| [`IAIThreadServerInfo`](../namespaces/AIThreadInfo/interfaces/IAIThreadServerInfo.md)

Defined in: [WAProto/index.d.ts:674](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L674)

#### Implementation of

[`IAIThreadInfo`](../interfaces/IAIThreadInfo.md).[`serverInfo`](../interfaces/IAIThreadInfo.md#serverinfo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L681)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIThreadInfo`](AIThreadInfo.md)

Defined in: [WAProto/index.d.ts:676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L676)

#### Parameters

##### properties?

[`IAIThreadInfo`](../interfaces/IAIThreadInfo.md)

#### Returns

[`AIThreadInfo`](AIThreadInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIThreadInfo`](AIThreadInfo.md)

Defined in: [WAProto/index.d.ts:678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L678)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIThreadInfo`](AIThreadInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L677)

#### Parameters

##### m

[`IAIThreadInfo`](../interfaces/IAIThreadInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIThreadInfo`](AIThreadInfo.md)

Defined in: [WAProto/index.d.ts:679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L679)

#### Parameters

##### d

#### Returns

[`AIThreadInfo`](AIThreadInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L682)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L680)

#### Parameters

##### m

[`AIThreadInfo`](AIThreadInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
