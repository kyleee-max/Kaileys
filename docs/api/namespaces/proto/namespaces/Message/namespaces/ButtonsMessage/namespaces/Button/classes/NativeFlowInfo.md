# Class: NativeFlowInfo

Defined in: [WAProto/index.d.ts:5696](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5696)

## Implements

- [`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

## Constructors

### new NativeFlowInfo()

> **new NativeFlowInfo**(`p`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:5697](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5697)

#### Parameters

##### p?

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

## Properties

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5698](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5698)

#### Implementation of

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md).[`name`](../interfaces/INativeFlowInfo.md#name)

***

### paramsJson?

> `optional` **paramsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5699)

#### Implementation of

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md).[`paramsJson`](../interfaces/INativeFlowInfo.md#paramsjson)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5705](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5705)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:5700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5700)

#### Parameters

##### properties?

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:5702](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5702)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5701](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5701)

#### Parameters

##### m

[`INativeFlowInfo`](../interfaces/INativeFlowInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NativeFlowInfo`](NativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:5703](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5703)

#### Parameters

##### d

#### Returns

[`NativeFlowInfo`](NativeFlowInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5706)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5704](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5704)

#### Parameters

##### m

[`NativeFlowInfo`](NativeFlowInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
