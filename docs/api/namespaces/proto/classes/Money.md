# Class: Money

Defined in: [WAProto/index.d.ts:9615](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9615)

## Implements

- [`IMoney`](../interfaces/IMoney.md)

## Constructors

### new Money()

> **new Money**(`p`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:9616](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9616)

#### Parameters

##### p?

[`IMoney`](../interfaces/IMoney.md)

#### Returns

[`Money`](Money.md)

## Properties

### currencyCode?

> `optional` **currencyCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9619](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9619)

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`currencyCode`](../interfaces/IMoney.md#currencycode)

***

### offset?

> `optional` **offset**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9618](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9618)

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`offset`](../interfaces/IMoney.md#offset)

***

### value?

> `optional` **value**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9617](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9617)

#### Implementation of

[`IMoney`](../interfaces/IMoney.md).[`value`](../interfaces/IMoney.md#value)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9625](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9625)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:9620](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9620)

#### Parameters

##### properties?

[`IMoney`](../interfaces/IMoney.md)

#### Returns

[`Money`](Money.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:9622](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9622)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Money`](Money.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9621](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9621)

#### Parameters

##### m

[`IMoney`](../interfaces/IMoney.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Money`](Money.md)

Defined in: [WAProto/index.d.ts:9623](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9623)

#### Parameters

##### d

#### Returns

[`Money`](Money.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9626](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9626)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9624](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9624)

#### Parameters

##### m

[`Money`](Money.md)

##### o?

`IConversionOptions`

#### Returns

`object`
