# Class: InteropData

Defined in: [WAProto/index.d.ts:2821](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2821)

## Implements

- [`IInteropData`](../interfaces/IInteropData.md)

## Constructors

### new InteropData()

> **new InteropData**(`p`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:2822](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2822)

#### Parameters

##### p?

[`IInteropData`](../interfaces/IInteropData.md)

#### Returns

[`InteropData`](InteropData.md)

## Properties

### accountId?

> `optional` **accountId**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2823](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2823)

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`accountId`](../interfaces/IInteropData.md#accountid)

***

### enableReadReceipts?

> `optional` **enableReadReceipts**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2825)

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`enableReadReceipts`](../interfaces/IInteropData.md#enablereadreceipts)

***

### token?

> `optional` **token**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2824)

#### Implementation of

[`IInteropData`](../interfaces/IInteropData.md).[`token`](../interfaces/IInteropData.md#token)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2831)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:2826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2826)

#### Parameters

##### properties?

[`IInteropData`](../interfaces/IInteropData.md)

#### Returns

[`InteropData`](InteropData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:2828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2828)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InteropData`](InteropData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2827)

#### Parameters

##### m

[`IInteropData`](../interfaces/IInteropData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InteropData`](InteropData.md)

Defined in: [WAProto/index.d.ts:2829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2829)

#### Parameters

##### d

#### Returns

[`InteropData`](InteropData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2832)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2830)

#### Parameters

##### m

[`InteropData`](InteropData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
