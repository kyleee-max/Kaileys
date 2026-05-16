# Class: KeyId

Defined in: [WAProto/index.d.ts:4937](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4937)

## Implements

- [`IKeyId`](../interfaces/IKeyId.md)

## Constructors

### new KeyId()

> **new KeyId**(`p`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:4938](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4938)

#### Parameters

##### p?

[`IKeyId`](../interfaces/IKeyId.md)

#### Returns

[`KeyId`](KeyId.md)

## Properties

### id?

> `optional` **id**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4939](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4939)

#### Implementation of

[`IKeyId`](../interfaces/IKeyId.md).[`id`](../interfaces/IKeyId.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4945](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4945)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:4940](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4940)

#### Parameters

##### properties?

[`IKeyId`](../interfaces/IKeyId.md)

#### Returns

[`KeyId`](KeyId.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:4942](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4942)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`KeyId`](KeyId.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4941](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4941)

#### Parameters

##### m

[`IKeyId`](../interfaces/IKeyId.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`KeyId`](KeyId.md)

Defined in: [WAProto/index.d.ts:4943](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4943)

#### Parameters

##### d

#### Returns

[`KeyId`](KeyId.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4946](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4946)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4944](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4944)

#### Parameters

##### m

[`KeyId`](KeyId.md)

##### o?

`IConversionOptions`

#### Returns

`object`
