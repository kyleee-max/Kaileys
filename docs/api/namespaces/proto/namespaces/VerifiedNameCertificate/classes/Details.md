# Class: Details

Defined in: [WAProto/index.d.ts:13452](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13452)

## Implements

- [`IDetails`](../interfaces/IDetails.md)

## Constructors

### new Details()

> **new Details**(`p`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:13453](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13453)

#### Parameters

##### p?

[`IDetails`](../interfaces/IDetails.md)

#### Returns

[`Details`](Details.md)

## Properties

### issuer?

> `optional` **issuer**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13455](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13455)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`issuer`](../interfaces/IDetails.md#issuer)

***

### issueTime?

> `optional` **issueTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13458)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`issueTime`](../interfaces/IDetails.md#issuetime)

***

### localizedNames

> **localizedNames**: [`ILocalizedName`](../../../interfaces/ILocalizedName.md)[]

Defined in: [WAProto/index.d.ts:13457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13457)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`localizedNames`](../interfaces/IDetails.md#localizednames)

***

### serial?

> `optional` **serial**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:13454](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13454)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`serial`](../interfaces/IDetails.md#serial)

***

### verifiedName?

> `optional` **verifiedName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13456)

#### Implementation of

[`IDetails`](../interfaces/IDetails.md).[`verifiedName`](../interfaces/IDetails.md#verifiedname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13464)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:13459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13459)

#### Parameters

##### properties?

[`IDetails`](../interfaces/IDetails.md)

#### Returns

[`Details`](Details.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Details`](Details.md)

Defined in: [WAProto/index.d.ts:13461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13461)

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

Defined in: [WAProto/index.d.ts:13460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13460)

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

Defined in: [WAProto/index.d.ts:13462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13462)

#### Parameters

##### d

#### Returns

[`Details`](Details.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13465)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13463)

#### Parameters

##### m

[`Details`](Details.md)

##### o?

`IConversionOptions`

#### Returns

`object`
