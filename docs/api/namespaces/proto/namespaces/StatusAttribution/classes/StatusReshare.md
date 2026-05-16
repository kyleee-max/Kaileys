# Class: StatusReshare

Defined in: [WAProto/index.d.ts:11270](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11270)

## Implements

- [`IStatusReshare`](../interfaces/IStatusReshare.md)

## Constructors

### new StatusReshare()

> **new StatusReshare**(`p`?): [`StatusReshare`](StatusReshare.md)

Defined in: [WAProto/index.d.ts:11271](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11271)

#### Parameters

##### p?

[`IStatusReshare`](../interfaces/IStatusReshare.md)

#### Returns

[`StatusReshare`](StatusReshare.md)

## Properties

### metadata?

> `optional` **metadata**: `null` \| [`IMetadata`](../namespaces/StatusReshare/interfaces/IMetadata.md)

Defined in: [WAProto/index.d.ts:11273](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11273)

#### Implementation of

[`IStatusReshare`](../interfaces/IStatusReshare.md).[`metadata`](../interfaces/IStatusReshare.md#metadata)

***

### source?

> `optional` **source**: `null` \| [`Source`](../namespaces/StatusReshare/enumerations/Source.md)

Defined in: [WAProto/index.d.ts:11272](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11272)

#### Implementation of

[`IStatusReshare`](../interfaces/IStatusReshare.md).[`source`](../interfaces/IStatusReshare.md#source)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11279](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11279)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusReshare`](StatusReshare.md)

Defined in: [WAProto/index.d.ts:11274](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11274)

#### Parameters

##### properties?

[`IStatusReshare`](../interfaces/IStatusReshare.md)

#### Returns

[`StatusReshare`](StatusReshare.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusReshare`](StatusReshare.md)

Defined in: [WAProto/index.d.ts:11276](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11276)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusReshare`](StatusReshare.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11275](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11275)

#### Parameters

##### m

[`IStatusReshare`](../interfaces/IStatusReshare.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusReshare`](StatusReshare.md)

Defined in: [WAProto/index.d.ts:11277](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11277)

#### Parameters

##### d

#### Returns

[`StatusReshare`](StatusReshare.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11280](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11280)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11278](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11278)

#### Parameters

##### m

[`StatusReshare`](StatusReshare.md)

##### o?

`IConversionOptions`

#### Returns

`object`
