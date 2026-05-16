# Class: Chat

Defined in: [WAProto/index.d.ts:5873](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5873)

## Implements

- [`IChat`](../interfaces/IChat.md)

## Constructors

### new Chat()

> **new Chat**(`p`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:5874](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5874)

#### Parameters

##### p?

[`IChat`](../interfaces/IChat.md)

#### Returns

[`Chat`](Chat.md)

## Properties

### displayName?

> `optional` **displayName**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5875)

#### Implementation of

[`IChat`](../interfaces/IChat.md).[`displayName`](../interfaces/IChat.md#displayname)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5876)

#### Implementation of

[`IChat`](../interfaces/IChat.md).[`id`](../interfaces/IChat.md#id)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5882)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:5877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5877)

#### Parameters

##### properties?

[`IChat`](../interfaces/IChat.md)

#### Returns

[`Chat`](Chat.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:5879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5879)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Chat`](Chat.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5878)

#### Parameters

##### m

[`IChat`](../interfaces/IChat.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Chat`](Chat.md)

Defined in: [WAProto/index.d.ts:5880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5880)

#### Parameters

##### d

#### Returns

[`Chat`](Chat.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5883)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5881)

#### Parameters

##### m

[`Chat`](Chat.md)

##### o?

`IConversionOptions`

#### Returns

`object`
