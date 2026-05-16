# Class: Parameters

Defined in: [WAProto/index.d.ts:3339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3339)

## Implements

- [`IParameters`](../interfaces/IParameters.md)

## Constructors

### new Parameters()

> **new Parameters**(`p`?): [`Parameters`](Parameters.md)

Defined in: [WAProto/index.d.ts:3340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3340)

#### Parameters

##### p?

[`IParameters`](../interfaces/IParameters.md)

#### Returns

[`Parameters`](Parameters.md)

## Properties

### contents?

> `optional` **contents**: `null` \| [`IParameters`](../interfaces/IParameters.md)

Defined in: [WAProto/index.d.ts:3345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3345)

#### Implementation of

[`IParameters`](../interfaces/IParameters.md).[`contents`](../interfaces/IParameters.md#contents)

***

### floatData?

> `optional` **floatData**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3344)

#### Implementation of

[`IParameters`](../interfaces/IParameters.md).[`floatData`](../interfaces/IParameters.md#floatdata)

***

### intData?

> `optional` **intData**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:3343](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3343)

#### Implementation of

[`IParameters`](../interfaces/IParameters.md).[`intData`](../interfaces/IParameters.md#intdata)

***

### key?

> `optional` **key**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3341)

#### Implementation of

[`IParameters`](../interfaces/IParameters.md).[`key`](../interfaces/IParameters.md#key)

***

### stringData?

> `optional` **stringData**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3342)

#### Implementation of

[`IParameters`](../interfaces/IParameters.md).[`stringData`](../interfaces/IParameters.md#stringdata)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3351)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Parameters`](Parameters.md)

Defined in: [WAProto/index.d.ts:3346](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3346)

#### Parameters

##### properties?

[`IParameters`](../interfaces/IParameters.md)

#### Returns

[`Parameters`](Parameters.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Parameters`](Parameters.md)

Defined in: [WAProto/index.d.ts:3348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3348)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Parameters`](Parameters.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3347)

#### Parameters

##### m

[`IParameters`](../interfaces/IParameters.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Parameters`](Parameters.md)

Defined in: [WAProto/index.d.ts:3349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3349)

#### Parameters

##### d

#### Returns

[`Parameters`](Parameters.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3352](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3352)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3350)

#### Parameters

##### m

[`Parameters`](Parameters.md)

##### o?

`IConversionOptions`

#### Returns

`object`
