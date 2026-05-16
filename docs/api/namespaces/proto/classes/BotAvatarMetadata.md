# Class: BotAvatarMetadata

Defined in: [WAProto/index.d.ts:948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L948)

## Implements

- [`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

## Constructors

### new BotAvatarMetadata()

> **new BotAvatarMetadata**(`p`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L949)

#### Parameters

##### p?

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

## Properties

### action?

> `optional` **action**: `null` \| `number`

Defined in: [WAProto/index.d.ts:952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L952)

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`action`](../interfaces/IBotAvatarMetadata.md#action)

***

### behaviorGraph?

> `optional` **behaviorGraph**: `null` \| `string`

Defined in: [WAProto/index.d.ts:951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L951)

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`behaviorGraph`](../interfaces/IBotAvatarMetadata.md#behaviorgraph)

***

### intensity?

> `optional` **intensity**: `null` \| `number`

Defined in: [WAProto/index.d.ts:953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L953)

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`intensity`](../interfaces/IBotAvatarMetadata.md#intensity)

***

### sentiment?

> `optional` **sentiment**: `null` \| `number`

Defined in: [WAProto/index.d.ts:950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L950)

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`sentiment`](../interfaces/IBotAvatarMetadata.md#sentiment)

***

### wordCount?

> `optional` **wordCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L954)

#### Implementation of

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md).[`wordCount`](../interfaces/IBotAvatarMetadata.md#wordcount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:960](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L960)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L955)

#### Parameters

##### properties?

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:957](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L957)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L956)

#### Parameters

##### m

[`IBotAvatarMetadata`](../interfaces/IBotAvatarMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotAvatarMetadata`](BotAvatarMetadata.md)

Defined in: [WAProto/index.d.ts:958](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L958)

#### Parameters

##### d

#### Returns

[`BotAvatarMetadata`](BotAvatarMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:961](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L961)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:959](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L959)

#### Parameters

##### m

[`BotAvatarMetadata`](BotAvatarMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
