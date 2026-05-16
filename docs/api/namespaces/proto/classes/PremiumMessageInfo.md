# Class: PremiumMessageInfo

Defined in: [WAProto/index.d.ts:10493](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10493)

## Implements

- [`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

## Constructors

### new PremiumMessageInfo()

> **new PremiumMessageInfo**(`p`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:10494](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10494)

#### Parameters

##### p?

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

## Properties

### serverCampaignId?

> `optional` **serverCampaignId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10495](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10495)

#### Implementation of

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md).[`serverCampaignId`](../interfaces/IPremiumMessageInfo.md#servercampaignid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10501](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10501)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:10496](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10496)

#### Parameters

##### properties?

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:10498](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10498)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10497](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10497)

#### Parameters

##### m

[`IPremiumMessageInfo`](../interfaces/IPremiumMessageInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PremiumMessageInfo`](PremiumMessageInfo.md)

Defined in: [WAProto/index.d.ts:10499](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10499)

#### Parameters

##### d

#### Returns

[`PremiumMessageInfo`](PremiumMessageInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10502](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10502)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10500](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10500)

#### Parameters

##### m

[`PremiumMessageInfo`](PremiumMessageInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
