# Class: PhotoChange

Defined in: [WAProto/index.d.ts:10316](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10316)

## Implements

- [`IPhotoChange`](../interfaces/IPhotoChange.md)

## Constructors

### new PhotoChange()

> **new PhotoChange**(`p`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:10317](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10317)

#### Parameters

##### p?

[`IPhotoChange`](../interfaces/IPhotoChange.md)

#### Returns

[`PhotoChange`](PhotoChange.md)

## Properties

### newPhoto?

> `optional` **newPhoto**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10319](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10319)

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`newPhoto`](../interfaces/IPhotoChange.md#newphoto)

***

### newPhotoId?

> `optional` **newPhotoId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10320)

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`newPhotoId`](../interfaces/IPhotoChange.md#newphotoid)

***

### oldPhoto?

> `optional` **oldPhoto**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10318)

#### Implementation of

[`IPhotoChange`](../interfaces/IPhotoChange.md).[`oldPhoto`](../interfaces/IPhotoChange.md#oldphoto)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10326](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10326)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:10321](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10321)

#### Parameters

##### properties?

[`IPhotoChange`](../interfaces/IPhotoChange.md)

#### Returns

[`PhotoChange`](PhotoChange.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:10323](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10323)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PhotoChange`](PhotoChange.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10322](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10322)

#### Parameters

##### m

[`IPhotoChange`](../interfaces/IPhotoChange.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PhotoChange`](PhotoChange.md)

Defined in: [WAProto/index.d.ts:10324](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10324)

#### Parameters

##### d

#### Returns

[`PhotoChange`](PhotoChange.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10327](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10327)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10325](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10325)

#### Parameters

##### m

[`PhotoChange`](PhotoChange.md)

##### o?

`IConversionOptions`

#### Returns

`object`
