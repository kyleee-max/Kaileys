# Class: Point

Defined in: [WAProto/index.d.ts:10370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10370)

## Implements

- [`IPoint`](../interfaces/IPoint.md)

## Constructors

### new Point()

> **new Point**(`p`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:10371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10371)

#### Parameters

##### p?

[`IPoint`](../interfaces/IPoint.md)

#### Returns

[`Point`](Point.md)

## Properties

### x?

> `optional` **x**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10374](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10374)

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`x`](../interfaces/IPoint.md#x)

***

### xDeprecated?

> `optional` **xDeprecated**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10372)

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`xDeprecated`](../interfaces/IPoint.md#xdeprecated)

***

### y?

> `optional` **y**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10375](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10375)

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`y`](../interfaces/IPoint.md#y)

***

### yDeprecated?

> `optional` **yDeprecated**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10373)

#### Implementation of

[`IPoint`](../interfaces/IPoint.md).[`yDeprecated`](../interfaces/IPoint.md#ydeprecated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10381](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10381)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:10376](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10376)

#### Parameters

##### properties?

[`IPoint`](../interfaces/IPoint.md)

#### Returns

[`Point`](Point.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:10378](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10378)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Point`](Point.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10377](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10377)

#### Parameters

##### m

[`IPoint`](../interfaces/IPoint.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Point`](Point.md)

Defined in: [WAProto/index.d.ts:10379](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10379)

#### Parameters

##### d

#### Returns

[`Point`](Point.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10382](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10382)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10380](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10380)

#### Parameters

##### m

[`Point`](Point.md)

##### o?

`IConversionOptions`

#### Returns

`object`
