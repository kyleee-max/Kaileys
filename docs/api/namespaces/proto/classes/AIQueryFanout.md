# Class: AIQueryFanout

Defined in: [WAProto/index.d.ts:187](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L187)

## Implements

- [`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

## Constructors

### new AIQueryFanout()

> **new AIQueryFanout**(`p`?): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:188](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L188)

#### Parameters

##### p?

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

## Properties

### message?

> `optional` **message**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:190](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L190)

#### Implementation of

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md).[`message`](../interfaces/IAIQueryFanout.md#message)

***

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:189](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L189)

#### Implementation of

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md).[`messageKey`](../interfaces/IAIQueryFanout.md#messagekey)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:191](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L191)

#### Implementation of

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md).[`timestamp`](../interfaces/IAIQueryFanout.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L197)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:192](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L192)

#### Parameters

##### properties?

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:194](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L194)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:193](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L193)

#### Parameters

##### m

[`IAIQueryFanout`](../interfaces/IAIQueryFanout.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIQueryFanout`](AIQueryFanout.md)

Defined in: [WAProto/index.d.ts:195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L195)

#### Parameters

##### d

#### Returns

[`AIQueryFanout`](AIQueryFanout.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L198)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L196)

#### Parameters

##### m

[`AIQueryFanout`](AIQueryFanout.md)

##### o?

`IConversionOptions`

#### Returns

`object`
