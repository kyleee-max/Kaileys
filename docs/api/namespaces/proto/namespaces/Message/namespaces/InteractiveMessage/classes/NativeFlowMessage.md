# Class: NativeFlowMessage

Defined in: [WAProto/index.d.ts:6892](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6892)

## Implements

- [`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

## Constructors

### new NativeFlowMessage()

> **new NativeFlowMessage**(`p`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:6893](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6893)

#### Parameters

##### p?

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

## Properties

### buttons

> **buttons**: [`INativeFlowButton`](../namespaces/NativeFlowMessage/interfaces/INativeFlowButton.md)[]

Defined in: [WAProto/index.d.ts:6894](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6894)

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`buttons`](../interfaces/INativeFlowMessage.md#buttons)

***

### messageParamsJson?

> `optional` **messageParamsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6895](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6895)

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`messageParamsJson`](../interfaces/INativeFlowMessage.md#messageparamsjson)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6896)

#### Implementation of

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md).[`messageVersion`](../interfaces/INativeFlowMessage.md#messageversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6902](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6902)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:6897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6897)

#### Parameters

##### properties?

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:6899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6899)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6898)

#### Parameters

##### m

[`INativeFlowMessage`](../interfaces/INativeFlowMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NativeFlowMessage`](NativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:6900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6900)

#### Parameters

##### d

#### Returns

[`NativeFlowMessage`](NativeFlowMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6903](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6903)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6901)

#### Parameters

##### m

[`NativeFlowMessage`](NativeFlowMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
