# Class: MsgRowOpaqueData

Defined in: [WAProto/index.d.ts:9826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9826)

## Implements

- [`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

## Constructors

### new MsgRowOpaqueData()

> **new MsgRowOpaqueData**(`p`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:9827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9827)

#### Parameters

##### p?

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

## Properties

### currentMsg?

> `optional` **currentMsg**: `null` \| [`IMsgOpaqueData`](../interfaces/IMsgOpaqueData.md)

Defined in: [WAProto/index.d.ts:9828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9828)

#### Implementation of

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md).[`currentMsg`](../interfaces/IMsgRowOpaqueData.md#currentmsg)

***

### quotedMsg?

> `optional` **quotedMsg**: `null` \| [`IMsgOpaqueData`](../interfaces/IMsgOpaqueData.md)

Defined in: [WAProto/index.d.ts:9829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9829)

#### Implementation of

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md).[`quotedMsg`](../interfaces/IMsgRowOpaqueData.md#quotedmsg)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9835)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:9830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9830)

#### Parameters

##### properties?

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:9832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9832)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9831)

#### Parameters

##### m

[`IMsgRowOpaqueData`](../interfaces/IMsgRowOpaqueData.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MsgRowOpaqueData`](MsgRowOpaqueData.md)

Defined in: [WAProto/index.d.ts:9833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9833)

#### Parameters

##### d

#### Returns

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9836](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9836)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9834)

#### Parameters

##### m

[`MsgRowOpaqueData`](MsgRowOpaqueData.md)

##### o?

`IConversionOptions`

#### Returns

`object`
