# Class: StatusMentionMessage

Defined in: [WAProto/index.d.ts:11333](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11333)

## Implements

- [`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

## Constructors

### new StatusMentionMessage()

> **new StatusMentionMessage**(`p`?): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:11334](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11334)

#### Parameters

##### p?

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

## Properties

### quotedStatus?

> `optional` **quotedStatus**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:11335](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11335)

#### Implementation of

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md).[`quotedStatus`](../interfaces/IStatusMentionMessage.md#quotedstatus)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11341)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:11336](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11336)

#### Parameters

##### properties?

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:11338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11338)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11337](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11337)

#### Parameters

##### m

[`IStatusMentionMessage`](../interfaces/IStatusMentionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusMentionMessage`](StatusMentionMessage.md)

Defined in: [WAProto/index.d.ts:11339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11339)

#### Parameters

##### d

#### Returns

[`StatusMentionMessage`](StatusMentionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11342)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11340)

#### Parameters

##### m

[`StatusMentionMessage`](StatusMentionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
