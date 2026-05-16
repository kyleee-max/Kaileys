# Class: KeepInChatMessage

Defined in: [WAProto/index.d.ts:7076](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7076)

## Implements

- [`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

## Constructors

### new KeepInChatMessage()

> **new KeepInChatMessage**(`p`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:7077](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7077)

#### Parameters

##### p?

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

## Properties

### keepType?

> `optional` **keepType**: `null` \| [`KeepType`](../../../enumerations/KeepType.md)

Defined in: [WAProto/index.d.ts:7079](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7079)

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`keepType`](../interfaces/IKeepInChatMessage.md#keeptype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:7078](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7078)

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`key`](../interfaces/IKeepInChatMessage.md#key)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7080](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7080)

#### Implementation of

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md).[`timestampMs`](../interfaces/IKeepInChatMessage.md#timestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7086](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7086)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:7081](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7081)

#### Parameters

##### properties?

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:7083](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7083)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7082](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7082)

#### Parameters

##### m

[`IKeepInChatMessage`](../interfaces/IKeepInChatMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`KeepInChatMessage`](KeepInChatMessage.md)

Defined in: [WAProto/index.d.ts:7084](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7084)

#### Parameters

##### d

#### Returns

[`KeepInChatMessage`](KeepInChatMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7087](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7087)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7085](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7085)

#### Parameters

##### m

[`KeepInChatMessage`](KeepInChatMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
