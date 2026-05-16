# Class: HandshakeMessage

Defined in: [WAProto/index.d.ts:4434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4434)

## Implements

- [`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

## Constructors

### new HandshakeMessage()

> **new HandshakeMessage**(`p`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:4435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4435)

#### Parameters

##### p?

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

## Properties

### clientFinish?

> `optional` **clientFinish**: `null` \| [`IClientFinish`](../namespaces/HandshakeMessage/interfaces/IClientFinish.md)

Defined in: [WAProto/index.d.ts:4438](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4438)

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`clientFinish`](../interfaces/IHandshakeMessage.md#clientfinish)

***

### clientHello?

> `optional` **clientHello**: `null` \| [`IClientHello`](../namespaces/HandshakeMessage/interfaces/IClientHello.md)

Defined in: [WAProto/index.d.ts:4436](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4436)

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`clientHello`](../interfaces/IHandshakeMessage.md#clienthello)

***

### serverHello?

> `optional` **serverHello**: `null` \| [`IServerHello`](../namespaces/HandshakeMessage/interfaces/IServerHello.md)

Defined in: [WAProto/index.d.ts:4437](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4437)

#### Implementation of

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md).[`serverHello`](../interfaces/IHandshakeMessage.md#serverhello)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4444)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:4439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4439)

#### Parameters

##### properties?

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:4441](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4441)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4440)

#### Parameters

##### m

[`IHandshakeMessage`](../interfaces/IHandshakeMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HandshakeMessage`](HandshakeMessage.md)

Defined in: [WAProto/index.d.ts:4442](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4442)

#### Parameters

##### d

#### Returns

[`HandshakeMessage`](HandshakeMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4445](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4445)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4443)

#### Parameters

##### m

[`HandshakeMessage`](HandshakeMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
