# Class: StatusAudienceMetadata

Defined in: [WAProto/index.d.ts:3553](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3553)

## Implements

- [`IStatusAudienceMetadata`](../interfaces/IStatusAudienceMetadata.md)

## Constructors

### new StatusAudienceMetadata()

> **new StatusAudienceMetadata**(`p`?): [`StatusAudienceMetadata`](StatusAudienceMetadata.md)

Defined in: [WAProto/index.d.ts:3554](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3554)

#### Parameters

##### p?

[`IStatusAudienceMetadata`](../interfaces/IStatusAudienceMetadata.md)

#### Returns

[`StatusAudienceMetadata`](StatusAudienceMetadata.md)

## Properties

### audienceType?

> `optional` **audienceType**: `null` \| [`AudienceType`](../namespaces/StatusAudienceMetadata/enumerations/AudienceType.md)

Defined in: [WAProto/index.d.ts:3555](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3555)

#### Implementation of

[`IStatusAudienceMetadata`](../interfaces/IStatusAudienceMetadata.md).[`audienceType`](../interfaces/IStatusAudienceMetadata.md#audiencetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3561](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3561)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusAudienceMetadata`](StatusAudienceMetadata.md)

Defined in: [WAProto/index.d.ts:3556](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3556)

#### Parameters

##### properties?

[`IStatusAudienceMetadata`](../interfaces/IStatusAudienceMetadata.md)

#### Returns

[`StatusAudienceMetadata`](StatusAudienceMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusAudienceMetadata`](StatusAudienceMetadata.md)

Defined in: [WAProto/index.d.ts:3558](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3558)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusAudienceMetadata`](StatusAudienceMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3557](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3557)

#### Parameters

##### m

[`IStatusAudienceMetadata`](../interfaces/IStatusAudienceMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusAudienceMetadata`](StatusAudienceMetadata.md)

Defined in: [WAProto/index.d.ts:3559](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3559)

#### Parameters

##### d

#### Returns

[`StatusAudienceMetadata`](StatusAudienceMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3562](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3562)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3560](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3560)

#### Parameters

##### m

[`StatusAudienceMetadata`](StatusAudienceMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
