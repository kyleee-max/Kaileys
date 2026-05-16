# Class: SyncdValue

Defined in: [WAProto/index.d.ts:13126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13126)

## Implements

- [`ISyncdValue`](../interfaces/ISyncdValue.md)

## Constructors

### new SyncdValue()

> **new SyncdValue**(`p`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:13127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13127)

#### Parameters

##### p?

[`ISyncdValue`](../interfaces/ISyncdValue.md)

#### Returns

[`SyncdValue`](SyncdValue.md)

## Properties

### blob?

> `optional` **blob**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:13128](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13128)

#### Implementation of

[`ISyncdValue`](../interfaces/ISyncdValue.md).[`blob`](../interfaces/ISyncdValue.md#blob)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13134](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13134)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:13129](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13129)

#### Parameters

##### properties?

[`ISyncdValue`](../interfaces/ISyncdValue.md)

#### Returns

[`SyncdValue`](SyncdValue.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:13131](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13131)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SyncdValue`](SyncdValue.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13130](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13130)

#### Parameters

##### m

[`ISyncdValue`](../interfaces/ISyncdValue.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SyncdValue`](SyncdValue.md)

Defined in: [WAProto/index.d.ts:13132](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13132)

#### Parameters

##### d

#### Returns

[`SyncdValue`](SyncdValue.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13135](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13135)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13133](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13133)

#### Parameters

##### m

[`SyncdValue`](SyncdValue.md)

##### o?

`IConversionOptions`

#### Returns

`object`
