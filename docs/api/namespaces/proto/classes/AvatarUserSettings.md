# Class: AvatarUserSettings

Defined in: [WAProto/index.d.ts:796](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L796)

## Implements

- [`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

## Constructors

### new AvatarUserSettings()

> **new AvatarUserSettings**(`p`?): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:797](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L797)

#### Parameters

##### p?

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

## Properties

### fbid?

> `optional` **fbid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L798)

#### Implementation of

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md).[`fbid`](../interfaces/IAvatarUserSettings.md#fbid)

***

### password?

> `optional` **password**: `null` \| `string`

Defined in: [WAProto/index.d.ts:799](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L799)

#### Implementation of

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md).[`password`](../interfaces/IAvatarUserSettings.md#password)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:805](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L805)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L800)

#### Parameters

##### properties?

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:802](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L802)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L801)

#### Parameters

##### m

[`IAvatarUserSettings`](../interfaces/IAvatarUserSettings.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AvatarUserSettings`](AvatarUserSettings.md)

Defined in: [WAProto/index.d.ts:803](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L803)

#### Parameters

##### d

#### Returns

[`AvatarUserSettings`](AvatarUserSettings.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L806)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:804](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L804)

#### Parameters

##### m

[`AvatarUserSettings`](AvatarUserSettings.md)

##### o?

`IConversionOptions`

#### Returns

`object`
