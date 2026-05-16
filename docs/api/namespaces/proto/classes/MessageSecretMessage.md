# Class: MessageSecretMessage

Defined in: [WAProto/index.d.ts:9595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9595)

## Implements

- [`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

## Constructors

### new MessageSecretMessage()

> **new MessageSecretMessage**(`p`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:9596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9596)

#### Parameters

##### p?

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9598)

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`encIv`](../interfaces/IMessageSecretMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9599)

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`encPayload`](../interfaces/IMessageSecretMessage.md#encpayload)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9597)

#### Implementation of

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md).[`version`](../interfaces/IMessageSecretMessage.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9605](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9605)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:9600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9600)

#### Parameters

##### properties?

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:9602](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9602)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9601](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9601)

#### Parameters

##### m

[`IMessageSecretMessage`](../interfaces/IMessageSecretMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageSecretMessage`](MessageSecretMessage.md)

Defined in: [WAProto/index.d.ts:9603](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9603)

#### Parameters

##### d

#### Returns

[`MessageSecretMessage`](MessageSecretMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9606](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9606)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9604](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9604)

#### Parameters

##### m

[`MessageSecretMessage`](MessageSecretMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
