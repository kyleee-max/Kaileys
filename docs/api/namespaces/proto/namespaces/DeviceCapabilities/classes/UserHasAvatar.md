# Class: UserHasAvatar

Defined in: [WAProto/index.d.ts:3806](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3806)

## Implements

- [`IUserHasAvatar`](../interfaces/IUserHasAvatar.md)

## Constructors

### new UserHasAvatar()

> **new UserHasAvatar**(`p`?): [`UserHasAvatar`](UserHasAvatar.md)

Defined in: [WAProto/index.d.ts:3807](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3807)

#### Parameters

##### p?

[`IUserHasAvatar`](../interfaces/IUserHasAvatar.md)

#### Returns

[`UserHasAvatar`](UserHasAvatar.md)

## Properties

### userHasAvatar?

> `optional` **userHasAvatar**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3808)

#### Implementation of

[`IUserHasAvatar`](../interfaces/IUserHasAvatar.md).[`userHasAvatar`](../interfaces/IUserHasAvatar.md#userhasavatar)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3814](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3814)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UserHasAvatar`](UserHasAvatar.md)

Defined in: [WAProto/index.d.ts:3809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3809)

#### Parameters

##### properties?

[`IUserHasAvatar`](../interfaces/IUserHasAvatar.md)

#### Returns

[`UserHasAvatar`](UserHasAvatar.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UserHasAvatar`](UserHasAvatar.md)

Defined in: [WAProto/index.d.ts:3811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3811)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UserHasAvatar`](UserHasAvatar.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3810)

#### Parameters

##### m

[`IUserHasAvatar`](../interfaces/IUserHasAvatar.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UserHasAvatar`](UserHasAvatar.md)

Defined in: [WAProto/index.d.ts:3812](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3812)

#### Parameters

##### d

#### Returns

[`UserHasAvatar`](UserHasAvatar.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3815](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3815)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3813](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3813)

#### Parameters

##### m

[`UserHasAvatar`](UserHasAvatar.md)

##### o?

`IConversionOptions`

#### Returns

`object`
