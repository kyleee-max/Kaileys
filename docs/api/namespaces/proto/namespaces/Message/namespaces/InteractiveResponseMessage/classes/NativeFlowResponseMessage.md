# Class: NativeFlowResponseMessage

Defined in: [WAProto/index.d.ts:7013](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7013)

## Implements

- [`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

## Constructors

### new NativeFlowResponseMessage()

> **new NativeFlowResponseMessage**(`p`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:7014](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7014)

#### Parameters

##### p?

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

## Properties

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7015](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7015)

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`name`](../interfaces/INativeFlowResponseMessage.md#name)

***

### paramsJson?

> `optional` **paramsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7016](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7016)

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`paramsJson`](../interfaces/INativeFlowResponseMessage.md#paramsjson)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7017](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7017)

#### Implementation of

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md).[`version`](../interfaces/INativeFlowResponseMessage.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7023](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7023)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:7018](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7018)

#### Parameters

##### properties?

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:7020](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7020)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7019](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7019)

#### Parameters

##### m

[`INativeFlowResponseMessage`](../interfaces/INativeFlowResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:7021](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7021)

#### Parameters

##### d

#### Returns

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7024)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7022](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7022)

#### Parameters

##### m

[`NativeFlowResponseMessage`](NativeFlowResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
