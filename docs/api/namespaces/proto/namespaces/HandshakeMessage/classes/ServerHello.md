# Class: ServerHello

Defined in: [WAProto/index.d.ts:4501](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4501)

## Implements

- [`IServerHello`](../interfaces/IServerHello.md)

## Constructors

### new ServerHello()

> **new ServerHello**(`p`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:4502](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4502)

#### Parameters

##### p?

[`IServerHello`](../interfaces/IServerHello.md)

#### Returns

[`ServerHello`](ServerHello.md)

## Properties

### ephemeral?

> `optional` **ephemeral**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4503)

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`ephemeral`](../interfaces/IServerHello.md#ephemeral)

***

### extendedStatic?

> `optional` **extendedStatic**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4506)

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`extendedStatic`](../interfaces/IServerHello.md#extendedstatic)

***

### payload?

> `optional` **payload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4505)

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`payload`](../interfaces/IServerHello.md#payload)

***

### static?

> `optional` **static**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4504)

#### Implementation of

[`IServerHello`](../interfaces/IServerHello.md).[`static`](../interfaces/IServerHello.md#static)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4512](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4512)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:4507](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4507)

#### Parameters

##### properties?

[`IServerHello`](../interfaces/IServerHello.md)

#### Returns

[`ServerHello`](ServerHello.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:4509](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4509)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ServerHello`](ServerHello.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4508](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4508)

#### Parameters

##### m

[`IServerHello`](../interfaces/IServerHello.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ServerHello`](ServerHello.md)

Defined in: [WAProto/index.d.ts:4510](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4510)

#### Parameters

##### d

#### Returns

[`ServerHello`](ServerHello.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4513](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4513)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4511](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4511)

#### Parameters

##### m

[`ServerHello`](ServerHello.md)

##### o?

`IConversionOptions`

#### Returns

`object`
