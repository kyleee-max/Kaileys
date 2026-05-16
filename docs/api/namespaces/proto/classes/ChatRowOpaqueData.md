# Class: ChatRowOpaqueData

Defined in: [WAProto/index.d.ts:2479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2479)

## Implements

- [`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

## Constructors

### new ChatRowOpaqueData()

> **new ChatRowOpaqueData**(`p`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2480)

#### Parameters

##### p?

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

## Properties

### draftMessage?

> `optional` **draftMessage**: `null` \| [`IDraftMessage`](../namespaces/ChatRowOpaqueData/interfaces/IDraftMessage.md)

Defined in: [WAProto/index.d.ts:2481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2481)

#### Implementation of

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md).[`draftMessage`](../interfaces/IChatRowOpaqueData.md#draftmessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2487)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2482)

#### Parameters

##### properties?

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2484)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2483)

#### Parameters

##### m

[`IChatRowOpaqueData`](../interfaces/IChatRowOpaqueData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ChatRowOpaqueData`](ChatRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:2485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2485)

#### Parameters

##### d

#### Returns

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2488)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2486)

#### Parameters

##### m

[`ChatRowOpaqueData`](ChatRowOpaqueData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
