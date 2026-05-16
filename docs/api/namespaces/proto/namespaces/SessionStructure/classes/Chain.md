# Class: Chain

Defined in: [WAProto/index.d.ts:10923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10923)

## Implements

- [`IChain`](../interfaces/IChain.md)

## Constructors

### new Chain()

> **new Chain**(`p`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:10924](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10924)

#### Parameters

##### p?

[`IChain`](../interfaces/IChain.md)

#### Returns

[`Chain`](Chain.md)

## Properties

### chainKey?

> `optional` **chainKey**: `null` \| [`IChainKey`](../namespaces/Chain/interfaces/IChainKey.md)

Defined in: [WAProto/index.d.ts:10927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10927)

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`chainKey`](../interfaces/IChain.md#chainkey)

***

### messageKeys

> **messageKeys**: [`IMessageKey`](../namespaces/Chain/interfaces/IMessageKey.md)[]

Defined in: [WAProto/index.d.ts:10928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10928)

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`messageKeys`](../interfaces/IChain.md#messagekeys)

***

### senderRatchetKey?

> `optional` **senderRatchetKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10925)

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`senderRatchetKey`](../interfaces/IChain.md#senderratchetkey)

***

### senderRatchetKeyPrivate?

> `optional` **senderRatchetKeyPrivate**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10926)

#### Implementation of

[`IChain`](../interfaces/IChain.md).[`senderRatchetKeyPrivate`](../interfaces/IChain.md#senderratchetkeyprivate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10934)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:10929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10929)

#### Parameters

##### properties?

[`IChain`](../interfaces/IChain.md)

#### Returns

[`Chain`](Chain.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:10931](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10931)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Chain`](Chain.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10930](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10930)

#### Parameters

##### m

[`IChain`](../interfaces/IChain.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Chain`](Chain.md)

Defined in: [WAProto/index.d.ts:10932](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10932)

#### Parameters

##### d

#### Returns

[`Chain`](Chain.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10935)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10933)

#### Parameters

##### m

[`Chain`](Chain.md)

##### o?

`IConversionOptions`

#### Returns

`object`
