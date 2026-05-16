# Class: ServerErrorReceipt

Defined in: [WAProto/index.d.ts:10862](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10862)

## Implements

- [`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

## Constructors

### new ServerErrorReceipt()

> **new ServerErrorReceipt**(`p`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:10863](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10863)

#### Parameters

##### p?

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

## Properties

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10864](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10864)

#### Implementation of

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md).[`stanzaId`](../interfaces/IServerErrorReceipt.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10870](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10870)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:10865](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10865)

#### Parameters

##### properties?

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:10867](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10867)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10866](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10866)

#### Parameters

##### m

[`IServerErrorReceipt`](../interfaces/IServerErrorReceipt.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ServerErrorReceipt`](ServerErrorReceipt.md)

Defined in: [WAProto/index.d.ts:10868](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10868)

#### Parameters

##### d

#### Returns

[`ServerErrorReceipt`](ServerErrorReceipt.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10871](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10871)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10869](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10869)

#### Parameters

##### m

[`ServerErrorReceipt`](ServerErrorReceipt.md)

##### o?

`IConversionOptions`

#### Returns

`object`
