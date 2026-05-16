# Class: BotCapabilityMetadata

Defined in: [WAProto/index.d.ts:968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L968)

## Implements

- [`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

## Constructors

### new BotCapabilityMetadata()

> **new BotCapabilityMetadata**(`p`?): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L969)

#### Parameters

##### p?

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

## Properties

### capabilities

> **capabilities**: [`BotCapabilityType`](../namespaces/BotCapabilityMetadata/enumerations/BotCapabilityType.md)[]

Defined in: [WAProto/index.d.ts:970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L970)

#### Implementation of

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md).[`capabilities`](../interfaces/IBotCapabilityMetadata.md#capabilities)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:976](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L976)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L971)

#### Parameters

##### properties?

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L973)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L972)

#### Parameters

##### m

[`IBotCapabilityMetadata`](../interfaces/IBotCapabilityMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotCapabilityMetadata`](BotCapabilityMetadata.md)

Defined in: [WAProto/index.d.ts:974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L974)

#### Parameters

##### d

#### Returns

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:977](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L977)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:975](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L975)

#### Parameters

##### m

[`BotCapabilityMetadata`](BotCapabilityMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
