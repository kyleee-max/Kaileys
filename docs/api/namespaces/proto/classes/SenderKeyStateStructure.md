# Class: SenderKeyStateStructure

Defined in: [WAProto/index.d.ts:10786](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10786)

## Implements

- [`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

## Constructors

### new SenderKeyStateStructure()

> **new SenderKeyStateStructure**(`p`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:10787](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10787)

#### Parameters

##### p?

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

## Properties

### senderChainKey?

> `optional` **senderChainKey**: `null` \| [`ISenderChainKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderChainKey.md)

Defined in: [WAProto/index.d.ts:10789](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10789)

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderChainKey`](../interfaces/ISenderKeyStateStructure.md#senderchainkey)

***

### senderKeyId?

> `optional` **senderKeyId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10788](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10788)

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderKeyId`](../interfaces/ISenderKeyStateStructure.md#senderkeyid)

***

### senderMessageKeys

> **senderMessageKeys**: [`ISenderMessageKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderMessageKey.md)[]

Defined in: [WAProto/index.d.ts:10791](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10791)

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderMessageKeys`](../interfaces/ISenderKeyStateStructure.md#sendermessagekeys)

***

### senderSigningKey?

> `optional` **senderSigningKey**: `null` \| [`ISenderSigningKey`](../namespaces/SenderKeyStateStructure/interfaces/ISenderSigningKey.md)

Defined in: [WAProto/index.d.ts:10790](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10790)

#### Implementation of

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md).[`senderSigningKey`](../interfaces/ISenderKeyStateStructure.md#sendersigningkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10797](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10797)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:10792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10792)

#### Parameters

##### properties?

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:10794](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10794)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10793)

#### Parameters

##### m

[`ISenderKeyStateStructure`](../interfaces/ISenderKeyStateStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderKeyStateStructure`](SenderKeyStateStructure.md)

Defined in: [WAProto/index.d.ts:10795](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10795)

#### Parameters

##### d

#### Returns

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10798)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10796](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10796)

#### Parameters

##### m

[`SenderKeyStateStructure`](SenderKeyStateStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
