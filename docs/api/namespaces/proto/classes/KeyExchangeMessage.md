# Class: KeyExchangeMessage

Defined in: [WAProto/index.d.ts:4917](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4917)

## Implements

- [`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

## Constructors

### new KeyExchangeMessage()

> **new KeyExchangeMessage**(`p`?): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:4918](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4918)

#### Parameters

##### p?

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

## Properties

### baseKey?

> `optional` **baseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4920)

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`baseKey`](../interfaces/IKeyExchangeMessage.md#basekey)

***

### baseKeySignature?

> `optional` **baseKeySignature**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4923)

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`baseKeySignature`](../interfaces/IKeyExchangeMessage.md#basekeysignature)

***

### id?

> `optional` **id**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4919](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4919)

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`id`](../interfaces/IKeyExchangeMessage.md#id)

***

### identityKey?

> `optional` **identityKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4922](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4922)

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`identityKey`](../interfaces/IKeyExchangeMessage.md#identitykey)

***

### ratchetKey?

> `optional` **ratchetKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4921)

#### Implementation of

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md).[`ratchetKey`](../interfaces/IKeyExchangeMessage.md#ratchetkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4929)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:4924](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4924)

#### Parameters

##### properties?

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:4926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4926)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4925)

#### Parameters

##### m

[`IKeyExchangeMessage`](../interfaces/IKeyExchangeMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`KeyExchangeMessage`](KeyExchangeMessage.md)

Defined in: [WAProto/index.d.ts:4927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4927)

#### Parameters

##### d

#### Returns

[`KeyExchangeMessage`](KeyExchangeMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4930](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4930)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4928)

#### Parameters

##### m

[`KeyExchangeMessage`](KeyExchangeMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
