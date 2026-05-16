# Class: AvatarUpdatedAction

Defined in: [WAProto/index.d.ts:11656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11656)

## Implements

- [`IAvatarUpdatedAction`](../interfaces/IAvatarUpdatedAction.md)

## Constructors

### new AvatarUpdatedAction()

> **new AvatarUpdatedAction**(`p`?): [`AvatarUpdatedAction`](AvatarUpdatedAction.md)

Defined in: [WAProto/index.d.ts:11657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11657)

#### Parameters

##### p?

[`IAvatarUpdatedAction`](../interfaces/IAvatarUpdatedAction.md)

#### Returns

[`AvatarUpdatedAction`](AvatarUpdatedAction.md)

## Properties

### eventType?

> `optional` **eventType**: `null` \| [`AvatarEventType`](../namespaces/AvatarUpdatedAction/enumerations/AvatarEventType.md)

Defined in: [WAProto/index.d.ts:11658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11658)

#### Implementation of

[`IAvatarUpdatedAction`](../interfaces/IAvatarUpdatedAction.md).[`eventType`](../interfaces/IAvatarUpdatedAction.md#eventtype)

***

### recentAvatarStickers

> **recentAvatarStickers**: [`IStickerAction`](../interfaces/IStickerAction.md)[]

Defined in: [WAProto/index.d.ts:11659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11659)

#### Implementation of

[`IAvatarUpdatedAction`](../interfaces/IAvatarUpdatedAction.md).[`recentAvatarStickers`](../interfaces/IAvatarUpdatedAction.md#recentavatarstickers)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11665](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11665)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AvatarUpdatedAction`](AvatarUpdatedAction.md)

Defined in: [WAProto/index.d.ts:11660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11660)

#### Parameters

##### properties?

[`IAvatarUpdatedAction`](../interfaces/IAvatarUpdatedAction.md)

#### Returns

[`AvatarUpdatedAction`](AvatarUpdatedAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AvatarUpdatedAction`](AvatarUpdatedAction.md)

Defined in: [WAProto/index.d.ts:11662](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11662)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AvatarUpdatedAction`](AvatarUpdatedAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11661)

#### Parameters

##### m

[`IAvatarUpdatedAction`](../interfaces/IAvatarUpdatedAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AvatarUpdatedAction`](AvatarUpdatedAction.md)

Defined in: [WAProto/index.d.ts:11663](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11663)

#### Parameters

##### d

#### Returns

[`AvatarUpdatedAction`](AvatarUpdatedAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11666](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11666)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11664](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11664)

#### Parameters

##### m

[`AvatarUpdatedAction`](AvatarUpdatedAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
