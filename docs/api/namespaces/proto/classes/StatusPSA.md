# Class: StatusPSA

Defined in: [WAProto/index.d.ts:11350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11350)

## Implements

- [`IStatusPSA`](../interfaces/IStatusPSA.md)

## Constructors

### new StatusPSA()

> **new StatusPSA**(`p`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:11351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11351)

#### Parameters

##### p?

[`IStatusPSA`](../interfaces/IStatusPSA.md)

#### Returns

[`StatusPSA`](StatusPSA.md)

## Properties

### campaignExpirationTimestamp?

> `optional` **campaignExpirationTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:11353](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11353)

#### Implementation of

[`IStatusPSA`](../interfaces/IStatusPSA.md).[`campaignExpirationTimestamp`](../interfaces/IStatusPSA.md#campaignexpirationtimestamp)

***

### campaignId

> **campaignId**: `number` \| `Long`

Defined in: [WAProto/index.d.ts:11352](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11352)

#### Implementation of

[`IStatusPSA`](../interfaces/IStatusPSA.md).[`campaignId`](../interfaces/IStatusPSA.md#campaignid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11359](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11359)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:11354](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11354)

#### Parameters

##### properties?

[`IStatusPSA`](../interfaces/IStatusPSA.md)

#### Returns

[`StatusPSA`](StatusPSA.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:11356](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11356)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusPSA`](StatusPSA.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11355](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11355)

#### Parameters

##### m

[`IStatusPSA`](../interfaces/IStatusPSA.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusPSA`](StatusPSA.md)

Defined in: [WAProto/index.d.ts:11357](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11357)

#### Parameters

##### d

#### Returns

[`StatusPSA`](StatusPSA.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11360](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11360)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11358](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11358)

#### Parameters

##### m

[`StatusPSA`](StatusPSA.md)

##### o?

`IConversionOptions`

#### Returns

`object`
