# Class: UGCBot

Defined in: [WAProto/index.d.ts:12880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12880)

## Implements

- [`IUGCBot`](../interfaces/IUGCBot.md)

## Constructors

### new UGCBot()

> **new UGCBot**(`p`?): [`UGCBot`](UGCBot.md)

Defined in: [WAProto/index.d.ts:12881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12881)

#### Parameters

##### p?

[`IUGCBot`](../interfaces/IUGCBot.md)

#### Returns

[`UGCBot`](UGCBot.md)

## Properties

### definition?

> `optional` **definition**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:12882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12882)

#### Implementation of

[`IUGCBot`](../interfaces/IUGCBot.md).[`definition`](../interfaces/IUGCBot.md#definition)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12888](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12888)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UGCBot`](UGCBot.md)

Defined in: [WAProto/index.d.ts:12883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12883)

#### Parameters

##### properties?

[`IUGCBot`](../interfaces/IUGCBot.md)

#### Returns

[`UGCBot`](UGCBot.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UGCBot`](UGCBot.md)

Defined in: [WAProto/index.d.ts:12885](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12885)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UGCBot`](UGCBot.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12884](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12884)

#### Parameters

##### m

[`IUGCBot`](../interfaces/IUGCBot.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UGCBot`](UGCBot.md)

Defined in: [WAProto/index.d.ts:12886](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12886)

#### Parameters

##### d

#### Returns

[`UGCBot`](UGCBot.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12889](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12889)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12887](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12887)

#### Parameters

##### m

[`UGCBot`](UGCBot.md)

##### o?

`IConversionOptions`

#### Returns

`object`
