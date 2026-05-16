# Class: AIThreadClientInfo

Defined in: [WAProto/index.d.ts:691](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L691)

## Implements

- [`IAIThreadClientInfo`](../interfaces/IAIThreadClientInfo.md)

## Constructors

### new AIThreadClientInfo()

> **new AIThreadClientInfo**(`p`?): [`AIThreadClientInfo`](AIThreadClientInfo.md)

Defined in: [WAProto/index.d.ts:692](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L692)

#### Parameters

##### p?

[`IAIThreadClientInfo`](../interfaces/IAIThreadClientInfo.md)

#### Returns

[`AIThreadClientInfo`](AIThreadClientInfo.md)

## Properties

### type?

> `optional` **type**: `null` \| [`AIThreadType`](../namespaces/AIThreadClientInfo/enumerations/AIThreadType.md)

Defined in: [WAProto/index.d.ts:693](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L693)

#### Implementation of

[`IAIThreadClientInfo`](../interfaces/IAIThreadClientInfo.md).[`type`](../interfaces/IAIThreadClientInfo.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L699)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIThreadClientInfo`](AIThreadClientInfo.md)

Defined in: [WAProto/index.d.ts:694](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L694)

#### Parameters

##### properties?

[`IAIThreadClientInfo`](../interfaces/IAIThreadClientInfo.md)

#### Returns

[`AIThreadClientInfo`](AIThreadClientInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIThreadClientInfo`](AIThreadClientInfo.md)

Defined in: [WAProto/index.d.ts:696](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L696)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIThreadClientInfo`](AIThreadClientInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:695](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L695)

#### Parameters

##### m

[`IAIThreadClientInfo`](../interfaces/IAIThreadClientInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIThreadClientInfo`](AIThreadClientInfo.md)

Defined in: [WAProto/index.d.ts:697](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L697)

#### Parameters

##### d

#### Returns

[`AIThreadClientInfo`](AIThreadClientInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L700)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:698](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L698)

#### Parameters

##### m

[`AIThreadClientInfo`](AIThreadClientInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
