# Class: BotModeSelectionMetadata

Defined in: [WAProto/index.d.ts:1652](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1652)

## Implements

- [`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

## Constructors

### new BotModeSelectionMetadata()

> **new BotModeSelectionMetadata**(`p`?): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:1653](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1653)

#### Parameters

##### p?

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

## Properties

### mode

> **mode**: [`BotUserSelectionMode`](../namespaces/BotModeSelectionMetadata/enumerations/BotUserSelectionMode.md)[]

Defined in: [WAProto/index.d.ts:1654](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1654)

#### Implementation of

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md).[`mode`](../interfaces/IBotModeSelectionMetadata.md#mode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1660)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:1655](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1655)

#### Parameters

##### properties?

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:1657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1657)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1656)

#### Parameters

##### m

[`IBotModeSelectionMetadata`](../interfaces/IBotModeSelectionMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

Defined in: [WAProto/index.d.ts:1658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1658)

#### Parameters

##### d

#### Returns

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1661)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1659)

#### Parameters

##### m

[`BotModeSelectionMetadata`](BotModeSelectionMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
