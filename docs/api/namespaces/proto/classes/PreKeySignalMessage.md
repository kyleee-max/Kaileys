# Class: PreKeySignalMessage

Defined in: [WAProto/index.d.ts:10472](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10472)

## Implements

- [`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

## Constructors

### new PreKeySignalMessage()

> **new PreKeySignalMessage**(`p`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:10473](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10473)

#### Parameters

##### p?

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

## Properties

### baseKey?

> `optional` **baseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10477)

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`baseKey`](../interfaces/IPreKeySignalMessage.md#basekey)

***

### identityKey?

> `optional` **identityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10478)

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`identityKey`](../interfaces/IPreKeySignalMessage.md#identitykey)

***

### message?

> `optional` **message**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10479)

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`message`](../interfaces/IPreKeySignalMessage.md#message)

***

### preKeyId?

> `optional` **preKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10475](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10475)

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`preKeyId`](../interfaces/IPreKeySignalMessage.md#prekeyid)

***

### registrationId?

> `optional` **registrationId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10474](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10474)

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`registrationId`](../interfaces/IPreKeySignalMessage.md#registrationid)

***

### signedPreKeyId?

> `optional` **signedPreKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10476](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10476)

#### Implementation of

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md).[`signedPreKeyId`](../interfaces/IPreKeySignalMessage.md#signedprekeyid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10485)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:10480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10480)

#### Parameters

##### properties?

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:10482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10482)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10481)

#### Parameters

##### m

[`IPreKeySignalMessage`](../interfaces/IPreKeySignalMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PreKeySignalMessage`](PreKeySignalMessage.md)

Defined in: [WAProto/index.d.ts:10483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10483)

#### Parameters

##### d

#### Returns

[`PreKeySignalMessage`](PreKeySignalMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10486)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10484)

#### Parameters

##### m

[`PreKeySignalMessage`](PreKeySignalMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
