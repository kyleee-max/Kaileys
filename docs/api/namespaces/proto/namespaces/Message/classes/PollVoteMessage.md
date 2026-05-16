# Class: PollVoteMessage

Defined in: [WAProto/index.d.ts:8457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8457)

## Implements

- [`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

## Constructors

### new PollVoteMessage()

> **new PollVoteMessage**(`p`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:8458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8458)

#### Parameters

##### p?

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

## Properties

### selectedOptions

> **selectedOptions**: `Uint8Array`\<`ArrayBufferLike`\>[]

Defined in: [WAProto/index.d.ts:8459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8459)

#### Implementation of

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md).[`selectedOptions`](../interfaces/IPollVoteMessage.md#selectedoptions)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8465)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:8460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8460)

#### Parameters

##### properties?

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:8462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8462)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8461)

#### Parameters

##### m

[`IPollVoteMessage`](../interfaces/IPollVoteMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollVoteMessage`](PollVoteMessage.md)

Defined in: [WAProto/index.d.ts:8463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8463)

#### Parameters

##### d

#### Returns

[`PollVoteMessage`](PollVoteMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8466](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8466)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8464)

#### Parameters

##### m

[`PollVoteMessage`](PollVoteMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
