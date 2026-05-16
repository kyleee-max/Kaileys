# Class: StatusPrivacyAction

Defined in: [WAProto/index.d.ts:12739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12739)

## Implements

- [`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

## Constructors

### new StatusPrivacyAction()

> **new StatusPrivacyAction**(`p`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:12740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12740)

#### Parameters

##### p?

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

## Properties

### mode?

> `optional` **mode**: `null` \| [`StatusDistributionMode`](../namespaces/StatusPrivacyAction/enumerations/StatusDistributionMode.md)

Defined in: [WAProto/index.d.ts:12741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12741)

#### Implementation of

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md).[`mode`](../interfaces/IStatusPrivacyAction.md#mode)

***

### userJid

> **userJid**: `string`[]

Defined in: [WAProto/index.d.ts:12742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12742)

#### Implementation of

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md).[`userJid`](../interfaces/IStatusPrivacyAction.md#userjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12748](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12748)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:12743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12743)

#### Parameters

##### properties?

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:12745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12745)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12744)

#### Parameters

##### m

[`IStatusPrivacyAction`](../interfaces/IStatusPrivacyAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusPrivacyAction`](StatusPrivacyAction.md)

Defined in: [WAProto/index.d.ts:12746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12746)

#### Parameters

##### d

#### Returns

[`StatusPrivacyAction`](StatusPrivacyAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12749](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12749)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12747)

#### Parameters

##### m

[`StatusPrivacyAction`](StatusPrivacyAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
