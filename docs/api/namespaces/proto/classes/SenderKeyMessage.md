# Class: SenderKeyMessage

Defined in: [WAProto/index.d.ts:10749](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10749)

## Implements

- [`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

## Constructors

### new SenderKeyMessage()

> **new SenderKeyMessage**(`p`?): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:10750](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10750)

#### Parameters

##### p?

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

## Properties

### ciphertext?

> `optional` **ciphertext**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10753](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10753)

#### Implementation of

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md).[`ciphertext`](../interfaces/ISenderKeyMessage.md#ciphertext)

***

### id?

> `optional` **id**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10751](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10751)

#### Implementation of

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md).[`id`](../interfaces/ISenderKeyMessage.md#id)

***

### iteration?

> `optional` **iteration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10752](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10752)

#### Implementation of

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md).[`iteration`](../interfaces/ISenderKeyMessage.md#iteration)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10759](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10759)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:10754](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10754)

#### Parameters

##### properties?

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:10756](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10756)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10755](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10755)

#### Parameters

##### m

[`ISenderKeyMessage`](../interfaces/ISenderKeyMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderKeyMessage`](SenderKeyMessage.md)

Defined in: [WAProto/index.d.ts:10757](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10757)

#### Parameters

##### d

#### Returns

[`SenderKeyMessage`](SenderKeyMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10760](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10760)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10758](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10758)

#### Parameters

##### m

[`SenderKeyMessage`](SenderKeyMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
