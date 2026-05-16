# Class: ClientFinish

Defined in: [WAProto/index.d.ts:4456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4456)

## Implements

- [`IClientFinish`](../interfaces/IClientFinish.md)

## Constructors

### new ClientFinish()

> **new ClientFinish**(`p`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:4457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4457)

#### Parameters

##### p?

[`IClientFinish`](../interfaces/IClientFinish.md)

#### Returns

[`ClientFinish`](ClientFinish.md)

## Properties

### extendedCiphertext?

> `optional` **extendedCiphertext**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4460)

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`extendedCiphertext`](../interfaces/IClientFinish.md#extendedciphertext)

***

### payload?

> `optional` **payload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4459)

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`payload`](../interfaces/IClientFinish.md#payload)

***

### static?

> `optional` **static**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4458)

#### Implementation of

[`IClientFinish`](../interfaces/IClientFinish.md).[`static`](../interfaces/IClientFinish.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4466](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4466)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:4461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4461)

#### Parameters

##### properties?

[`IClientFinish`](../interfaces/IClientFinish.md)

#### Returns

[`ClientFinish`](ClientFinish.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:4463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4463)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ClientFinish`](ClientFinish.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4462)

#### Parameters

##### m

[`IClientFinish`](../interfaces/IClientFinish.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ClientFinish`](ClientFinish.md)

Defined in: [WAProto/index.d.ts:4464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4464)

#### Parameters

##### d

#### Returns

[`ClientFinish`](ClientFinish.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4467](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4467)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4465)

#### Parameters

##### m

[`ClientFinish`](ClientFinish.md)

##### o?

`IConversionOptions`

#### Returns

`object`
