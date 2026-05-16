# Class: SenderChainKey

Defined in: [WAProto/index.d.ts:10808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10808)

## Implements

- [`ISenderChainKey`](../interfaces/ISenderChainKey.md)

## Constructors

### new SenderChainKey()

> **new SenderChainKey**(`p`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:10809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10809)

#### Parameters

##### p?

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

#### Returns

[`SenderChainKey`](SenderChainKey.md)

## Properties

### iteration?

> `optional` **iteration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10810)

#### Implementation of

[`ISenderChainKey`](../interfaces/ISenderChainKey.md).[`iteration`](../interfaces/ISenderChainKey.md#iteration)

***

### seed?

> `optional` **seed**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10811)

#### Implementation of

[`ISenderChainKey`](../interfaces/ISenderChainKey.md).[`seed`](../interfaces/ISenderChainKey.md#seed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10817](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10817)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:10812](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10812)

#### Parameters

##### properties?

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

#### Returns

[`SenderChainKey`](SenderChainKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:10814](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10814)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderChainKey`](SenderChainKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10813](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10813)

#### Parameters

##### m

[`ISenderChainKey`](../interfaces/ISenderChainKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderChainKey`](SenderChainKey.md)

Defined in: [WAProto/index.d.ts:10815](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10815)

#### Parameters

##### d

#### Returns

[`SenderChainKey`](SenderChainKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10818](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10818)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10816](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10816)

#### Parameters

##### m

[`SenderChainKey`](SenderChainKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
