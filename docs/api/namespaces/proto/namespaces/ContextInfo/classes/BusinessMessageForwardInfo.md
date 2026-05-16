# Class: BusinessMessageForwardInfo

Defined in: [WAProto/index.d.ts:3290](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3290)

## Implements

- [`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

## Constructors

### new BusinessMessageForwardInfo()

> **new BusinessMessageForwardInfo**(`p`?): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:3291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3291)

#### Parameters

##### p?

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

## Properties

### businessOwnerJid?

> `optional` **businessOwnerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3292](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3292)

#### Implementation of

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md).[`businessOwnerJid`](../interfaces/IBusinessMessageForwardInfo.md#businessownerjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3298](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3298)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:3293](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3293)

#### Parameters

##### properties?

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:3295](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3295)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3294](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3294)

#### Parameters

##### m

[`IBusinessMessageForwardInfo`](../interfaces/IBusinessMessageForwardInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

Defined in: [WAProto/index.d.ts:3296](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3296)

#### Parameters

##### d

#### Returns

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3299](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3299)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3297](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3297)

#### Parameters

##### m

[`BusinessMessageForwardInfo`](BusinessMessageForwardInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
