# Class: IdentityKeyPairStructure

Defined in: [WAProto/index.d.ts:4699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4699)

## Implements

- [`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

## Constructors

### new IdentityKeyPairStructure()

> **new IdentityKeyPairStructure**(`p`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:4700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4700)

#### Parameters

##### p?

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

## Properties

### privateKey?

> `optional` **privateKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4702](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4702)

#### Implementation of

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md).[`privateKey`](../interfaces/IIdentityKeyPairStructure.md#privatekey)

***

### publicKey?

> `optional` **publicKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:4701](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4701)

#### Implementation of

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md).[`publicKey`](../interfaces/IIdentityKeyPairStructure.md#publickey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4708](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4708)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:4703](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4703)

#### Parameters

##### properties?

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:4705](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4705)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4704](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4704)

#### Parameters

##### m

[`IIdentityKeyPairStructure`](../interfaces/IIdentityKeyPairStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

Defined in: [WAProto/index.d.ts:4706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4706)

#### Parameters

##### d

#### Returns

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4709)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4707](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4707)

#### Parameters

##### m

[`IdentityKeyPairStructure`](IdentityKeyPairStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
