# Class: SenderMessageKey

Defined in: [WAProto/index.d.ts:10826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10826)

## Implements

- [`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

## Constructors

### new SenderMessageKey()

> **new SenderMessageKey**(`p`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:10827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10827)

#### Parameters

##### p?

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

## Properties

### iteration?

> `optional` **iteration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10828)

#### Implementation of

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md).[`iteration`](../interfaces/ISenderMessageKey.md#iteration)

***

### seed?

> `optional` **seed**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10829)

#### Implementation of

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md).[`seed`](../interfaces/ISenderMessageKey.md#seed)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10835)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:10830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10830)

#### Parameters

##### properties?

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:10832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10832)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10831)

#### Parameters

##### m

[`ISenderMessageKey`](../interfaces/ISenderMessageKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderMessageKey`](SenderMessageKey.md)

Defined in: [WAProto/index.d.ts:10833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10833)

#### Parameters

##### d

#### Returns

[`SenderMessageKey`](SenderMessageKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10836](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10836)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10834)

#### Parameters

##### m

[`SenderMessageKey`](SenderMessageKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
