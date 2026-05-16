# Class: UnarchiveChatsSetting

Defined in: [WAProto/index.d.ts:12896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12896)

## Implements

- [`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

## Constructors

### new UnarchiveChatsSetting()

> **new UnarchiveChatsSetting**(`p`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:12897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12897)

#### Parameters

##### p?

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

## Properties

### unarchiveChats?

> `optional` **unarchiveChats**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12898)

#### Implementation of

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md).[`unarchiveChats`](../interfaces/IUnarchiveChatsSetting.md#unarchivechats)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12904)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:12899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12899)

#### Parameters

##### properties?

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:12901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12901)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12900)

#### Parameters

##### m

[`IUnarchiveChatsSetting`](../interfaces/IUnarchiveChatsSetting.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

Defined in: [WAProto/index.d.ts:12902](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12902)

#### Parameters

##### d

#### Returns

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12905)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12903](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12903)

#### Parameters

##### m

[`UnarchiveChatsSetting`](UnarchiveChatsSetting.md)

##### o?

`IConversionOptions`

#### Returns

`object`
