# Class: InteractiveResponseMessage

Defined in: [WAProto/index.d.ts:6964](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6964)

## Implements

- [`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

## Constructors

### new InteractiveResponseMessage()

> **new InteractiveResponseMessage**(`p`?): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:6965](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6965)

#### Parameters

##### p?

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| [`IBody`](../namespaces/InteractiveResponseMessage/interfaces/IBody.md)

Defined in: [WAProto/index.d.ts:6966](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6966)

#### Implementation of

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md).[`body`](../interfaces/IInteractiveResponseMessage.md#body)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:6967](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6967)

#### Implementation of

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md).[`contextInfo`](../interfaces/IInteractiveResponseMessage.md#contextinfo)

***

### interactiveResponseMessage?

> `optional` **interactiveResponseMessage**: `"nativeFlowResponseMessage"`

Defined in: [WAProto/index.d.ts:6969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6969)

***

### nativeFlowResponseMessage?

> `optional` **nativeFlowResponseMessage**: `null` \| [`INativeFlowResponseMessage`](../namespaces/InteractiveResponseMessage/interfaces/INativeFlowResponseMessage.md)

Defined in: [WAProto/index.d.ts:6968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6968)

#### Implementation of

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md).[`nativeFlowResponseMessage`](../interfaces/IInteractiveResponseMessage.md#nativeflowresponsemessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6975](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6975)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:6970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6970)

#### Parameters

##### properties?

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:6972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6972)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6971)

#### Parameters

##### m

[`IInteractiveResponseMessage`](../interfaces/IInteractiveResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InteractiveResponseMessage`](InteractiveResponseMessage.md)

Defined in: [WAProto/index.d.ts:6973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6973)

#### Parameters

##### d

#### Returns

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6976](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6976)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6974)

#### Parameters

##### m

[`InteractiveResponseMessage`](InteractiveResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
