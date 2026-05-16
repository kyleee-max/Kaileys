# Class: ClientHello

Defined in: [WAProto/index.d.ts:4478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4478)

## Implements

- [`IClientHello`](../interfaces/IClientHello.md)

## Constructors

### new ClientHello()

> **new ClientHello**(`p`?): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:4479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4479)

#### Parameters

##### p?

[`IClientHello`](../interfaces/IClientHello.md)

#### Returns

[`ClientHello`](ClientHello.md)

## Properties

### ephemeral?

> `optional` **ephemeral**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4480)

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`ephemeral`](../interfaces/IClientHello.md#ephemeral)

***

### extendedCiphertext?

> `optional` **extendedCiphertext**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4484)

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`extendedCiphertext`](../interfaces/IClientHello.md#extendedciphertext)

***

### payload?

> `optional` **payload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4482)

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`payload`](../interfaces/IClientHello.md#payload)

***

### static?

> `optional` **static**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4481)

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`static`](../interfaces/IClientHello.md#static)

***

### useExtended?

> `optional` **useExtended**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4483)

#### Implementation of

[`IClientHello`](../interfaces/IClientHello.md).[`useExtended`](../interfaces/IClientHello.md#useextended)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4490](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4490)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:4485](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4485)

#### Parameters

##### properties?

[`IClientHello`](../interfaces/IClientHello.md)

#### Returns

[`ClientHello`](ClientHello.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:4487](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4487)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ClientHello`](ClientHello.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4486](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4486)

#### Parameters

##### m

[`IClientHello`](../interfaces/IClientHello.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ClientHello`](ClientHello.md)

Defined in: [WAProto/index.d.ts:4488](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4488)

#### Parameters

##### d

#### Returns

[`ClientHello`](ClientHello.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4491](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4491)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4489](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4489)

#### Parameters

##### m

[`ClientHello`](ClientHello.md)

##### o?

`IConversionOptions`

#### Returns

`object`
