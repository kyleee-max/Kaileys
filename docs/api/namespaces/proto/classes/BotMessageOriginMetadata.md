# Class: BotMessageOriginMetadata

Defined in: [WAProto/index.d.ts:1466](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1466)

## Implements

- [`IBotMessageOriginMetadata`](../interfaces/IBotMessageOriginMetadata.md)

## Constructors

### new BotMessageOriginMetadata()

> **new BotMessageOriginMetadata**(`p`?): [`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

Defined in: [WAProto/index.d.ts:1467](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1467)

#### Parameters

##### p?

[`IBotMessageOriginMetadata`](../interfaces/IBotMessageOriginMetadata.md)

#### Returns

[`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

## Properties

### origins

> **origins**: [`IBotMessageOrigin`](../interfaces/IBotMessageOrigin.md)[]

Defined in: [WAProto/index.d.ts:1468](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1468)

#### Implementation of

[`IBotMessageOriginMetadata`](../interfaces/IBotMessageOriginMetadata.md).[`origins`](../interfaces/IBotMessageOriginMetadata.md#origins)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1474](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1474)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

Defined in: [WAProto/index.d.ts:1469](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1469)

#### Parameters

##### properties?

[`IBotMessageOriginMetadata`](../interfaces/IBotMessageOriginMetadata.md)

#### Returns

[`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

Defined in: [WAProto/index.d.ts:1471](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1471)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1470](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1470)

#### Parameters

##### m

[`IBotMessageOriginMetadata`](../interfaces/IBotMessageOriginMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

Defined in: [WAProto/index.d.ts:1472](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1472)

#### Parameters

##### d

#### Returns

[`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1475](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1475)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1473](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1473)

#### Parameters

##### m

[`BotMessageOriginMetadata`](BotMessageOriginMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
