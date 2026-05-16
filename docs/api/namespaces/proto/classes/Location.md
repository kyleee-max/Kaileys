# Class: Location

Defined in: [WAProto/index.d.ts:5079](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5079)

## Implements

- [`ILocation`](../interfaces/ILocation.md)

## Constructors

### new Location()

> **new Location**(`p`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:5080](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5080)

#### Parameters

##### p?

[`ILocation`](../interfaces/ILocation.md)

#### Returns

[`Location`](Location.md)

## Properties

### degreesLatitude?

> `optional` **degreesLatitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5081](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5081)

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`degreesLatitude`](../interfaces/ILocation.md#degreeslatitude)

***

### degreesLongitude?

> `optional` **degreesLongitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5082](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5082)

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`degreesLongitude`](../interfaces/ILocation.md#degreeslongitude)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5083](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5083)

#### Implementation of

[`ILocation`](../interfaces/ILocation.md).[`name`](../interfaces/ILocation.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5089](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5089)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:5084](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5084)

#### Parameters

##### properties?

[`ILocation`](../interfaces/ILocation.md)

#### Returns

[`Location`](Location.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:5086](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5086)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Location`](Location.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5085](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5085)

#### Parameters

##### m

[`ILocation`](../interfaces/ILocation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Location`](Location.md)

Defined in: [WAProto/index.d.ts:5087](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5087)

#### Parameters

##### d

#### Returns

[`Location`](Location.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5090](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5090)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5088](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5088)

#### Parameters

##### m

[`Location`](Location.md)

##### o?

`IConversionOptions`

#### Returns

`object`
