# Class: Details

Defined in: [WAProto/index.d.ts:2439](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2439)

## Implements

- [`IDetails`](../interfaces/IDetails.md)

## Constructors

### new Details()

> **new Details**(`p`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:2440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2440)

#### Parameters

##### p?

[`IDetails`](../interfaces/IDetails.md)

#### Returns

[`Details`](Details.md)

## Properties

### issuerSerial?

> `optional` **issuerSerial**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2442](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2442)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`issuerSerial`](../interfaces/IDetails.md#issuerserial)

***

### key?

> `optional` **key**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:2443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2443)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`key`](../interfaces/IDetails.md#key)

***

### notAfter?

> `optional` **notAfter**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2445](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2445)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`notAfter`](../interfaces/IDetails.md#notafter)

***

### notBefore?

> `optional` **notBefore**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:2444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2444)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`notBefore`](../interfaces/IDetails.md#notbefore)

***

### serial?

> `optional` **serial**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2441](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2441)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`serial`](../interfaces/IDetails.md#serial)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2451](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2451)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:2446](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2446)

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

#### Returns

[`Details`](Details.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:2448](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2448)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Details`](Details.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2447](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2447)

#### Parameters

##### m

[`IDetails`](../interfaces/IDetails.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:2449](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2449)

#### Parameters

##### d

#### Returns

[`Details`](Details.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2452](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2452)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2450](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2450)

#### Parameters

##### m

[`Details`](Details.md)

##### o?

`IConversionOptions`

#### Returns

`object`
