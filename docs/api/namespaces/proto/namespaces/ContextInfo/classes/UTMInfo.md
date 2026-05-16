# Class: UTMInfo

Defined in: [WAProto/index.d.ts:3587](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3587)

## Implements

- [`IUTMInfo`](../interfaces/IUTMInfo.md)

## Constructors

### new UTMInfo()

> **new UTMInfo**(`p`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:3588](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3588)

#### Parameters

##### p?

[`IUTMInfo`](../interfaces/IUTMInfo.md)

#### Returns

[`UTMInfo`](UTMInfo.md)

## Properties

### utmCampaign?

> `optional` **utmCampaign**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3590](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3590)

#### Implementation of

[`IUTMInfo`](../interfaces/IUTMInfo.md).[`utmCampaign`](../interfaces/IUTMInfo.md#utmcampaign)

***

### utmSource?

> `optional` **utmSource**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3589](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3589)

#### Implementation of

[`IUTMInfo`](../interfaces/IUTMInfo.md).[`utmSource`](../interfaces/IUTMInfo.md#utmsource)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3596)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:3591](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3591)

#### Parameters

##### properties?

[`IUTMInfo`](../interfaces/IUTMInfo.md)

#### Returns

[`UTMInfo`](UTMInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:3593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3593)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UTMInfo`](UTMInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3592)

#### Parameters

##### m

[`IUTMInfo`](../interfaces/IUTMInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UTMInfo`](UTMInfo.md)

Defined in: [WAProto/index.d.ts:3594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3594)

#### Parameters

##### d

#### Returns

[`UTMInfo`](UTMInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3597)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3595)

#### Parameters

##### m

[`UTMInfo`](UTMInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
