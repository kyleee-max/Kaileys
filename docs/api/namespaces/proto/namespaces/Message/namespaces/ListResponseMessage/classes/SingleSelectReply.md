# Class: SingleSelectReply

Defined in: [WAProto/index.d.ts:7318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7318)

## Implements

- [`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

## Constructors

### new SingleSelectReply()

> **new SingleSelectReply**(`p`?): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:7319](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7319)

#### Parameters

##### p?

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

## Properties

### selectedRowId?

> `optional` **selectedRowId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7320)

#### Implementation of

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md).[`selectedRowId`](../interfaces/ISingleSelectReply.md#selectedrowid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7326](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7326)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:7321](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7321)

#### Parameters

##### properties?

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:7323](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7323)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7322](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7322)

#### Parameters

##### m

[`ISingleSelectReply`](../interfaces/ISingleSelectReply.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SingleSelectReply`](SingleSelectReply.md)

Defined in: [WAProto/index.d.ts:7324](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7324)

#### Parameters

##### d

#### Returns

[`SingleSelectReply`](SingleSelectReply.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7327](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7327)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7325](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7325)

#### Parameters

##### m

[`SingleSelectReply`](SingleSelectReply.md)

##### o?

`IConversionOptions`

#### Returns

`object`
