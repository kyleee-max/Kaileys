# Class: Details

Defined in: [WAProto/index.d.ts:9943](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9943)

## Implements

- [`IDetails`](../interfaces/IDetails.md)

## Constructors

### new Details()

> **new Details**(`p`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:9944](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9944)

#### Parameters

##### p?

[`IDetails`](../interfaces/IDetails.md)

#### Returns

[`Details`](Details.md)

## Properties

### expires?

> `optional` **expires**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9947](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9947)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`expires`](../interfaces/IDetails.md#expires)

***

### issuer?

> `optional` **issuer**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9946](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9946)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`issuer`](../interfaces/IDetails.md#issuer)

***

### key?

> `optional` **key**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:9949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9949)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`key`](../interfaces/IDetails.md#key)

***

### serial?

> `optional` **serial**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9945](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9945)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`serial`](../interfaces/IDetails.md#serial)

***

### subject?

> `optional` **subject**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9948)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`subject`](../interfaces/IDetails.md#subject)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9955)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:9950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9950)

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

#### Returns

[`Details`](Details.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:9952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9952)

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

Defined in: [WAProto/index.d.ts:9951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9951)

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

Defined in: [WAProto/index.d.ts:9953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9953)

#### Parameters

##### d

#### Returns

[`Details`](Details.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9956)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9954)

#### Parameters

##### m

[`Details`](Details.md)

##### o?

`IConversionOptions`

#### Returns

`object`
