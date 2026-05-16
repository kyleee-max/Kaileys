# Class: GroupInviteMessage

Defined in: [WAProto/index.d.ts:6370](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6370)

## Implements

- [`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

## Constructors

### new GroupInviteMessage()

> **new GroupInviteMessage**(`p`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:6371](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6371)

#### Parameters

##### p?

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6377](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6377)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`caption`](../interfaces/IGroupInviteMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:6378](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6378)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`contextInfo`](../interfaces/IGroupInviteMessage.md#contextinfo)

***

### groupJid?

> `optional` **groupJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6372](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6372)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupJid`](../interfaces/IGroupInviteMessage.md#groupjid)

***

### groupName?

> `optional` **groupName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6375](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6375)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupName`](../interfaces/IGroupInviteMessage.md#groupname)

***

### groupType?

> `optional` **groupType**: `null` \| [`GroupType`](../namespaces/GroupInviteMessage/enumerations/GroupType.md)

Defined in: [WAProto/index.d.ts:6379](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6379)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`groupType`](../interfaces/IGroupInviteMessage.md#grouptype)

***

### inviteCode?

> `optional` **inviteCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6373](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6373)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`inviteCode`](../interfaces/IGroupInviteMessage.md#invitecode)

***

### inviteExpiration?

> `optional` **inviteExpiration**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6374](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6374)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`inviteExpiration`](../interfaces/IGroupInviteMessage.md#inviteexpiration)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:6376](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6376)

#### Implementation of

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md).[`jpegThumbnail`](../interfaces/IGroupInviteMessage.md#jpegthumbnail)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6385](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6385)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:6380](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6380)

#### Parameters

##### properties?

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:6382](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6382)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6381](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6381)

#### Parameters

##### m

[`IGroupInviteMessage`](../interfaces/IGroupInviteMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`GroupInviteMessage`](GroupInviteMessage.md)

Defined in: [WAProto/index.d.ts:6383](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6383)

#### Parameters

##### d

#### Returns

[`GroupInviteMessage`](GroupInviteMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6386](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6386)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6384](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6384)

#### Parameters

##### m

[`GroupInviteMessage`](GroupInviteMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
