# Class: RemoveRecentStickerAction

Defined in: [WAProto/index.d.ts:12690](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12690)

## Implements

- [`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

## Constructors

### new RemoveRecentStickerAction()

> **new RemoveRecentStickerAction**(`p`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:12691](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12691)

#### Parameters

##### p?

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

## Properties

### lastStickerSentTs?

> `optional` **lastStickerSentTs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12692](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12692)

#### Implementation of

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md).[`lastStickerSentTs`](../interfaces/IRemoveRecentStickerAction.md#laststickersentts)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12698](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12698)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:12693](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12693)

#### Parameters

##### properties?

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:12695](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12695)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12694](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12694)

#### Parameters

##### m

[`IRemoveRecentStickerAction`](../interfaces/IRemoveRecentStickerAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

Defined in: [WAProto/index.d.ts:12696](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12696)

#### Parameters

##### d

#### Returns

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12699](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12699)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12697](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12697)

#### Parameters

##### m

[`RemoveRecentStickerAction`](RemoveRecentStickerAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
