# Class: PinInChat

Defined in: [WAProto/index.d.ts:10338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10338)

## Implements

- [`IPinInChat`](../interfaces/IPinInChat.md)

## Constructors

### new PinInChat()

> **new PinInChat**(`p`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:10339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10339)

#### Parameters

##### p?

[`IPinInChat`](../interfaces/IPinInChat.md)

#### Returns

[`PinInChat`](PinInChat.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:10341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10341)

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`key`](../interfaces/IPinInChat.md#key)

***

### messageAddOnContextInfo?

> `optional` **messageAddOnContextInfo**: `null` \| [`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:10344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10344)

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`messageAddOnContextInfo`](../interfaces/IPinInChat.md#messageaddoncontextinfo)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10342)

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`senderTimestampMs`](../interfaces/IPinInChat.md#sendertimestampms)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:10343](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10343)

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`serverTimestampMs`](../interfaces/IPinInChat.md#servertimestampms)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/PinInChat/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:10340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10340)

#### Implementation of

[`IPinInChat`](../interfaces/IPinInChat.md).[`type`](../interfaces/IPinInChat.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10350)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:10345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10345)

#### Parameters

##### properties?

[`IPinInChat`](../interfaces/IPinInChat.md)

#### Returns

[`PinInChat`](PinInChat.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:10347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10347)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PinInChat`](PinInChat.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10346](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10346)

#### Parameters

##### m

[`IPinInChat`](../interfaces/IPinInChat.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PinInChat`](PinInChat.md)

Defined in: [WAProto/index.d.ts:10348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10348)

#### Parameters

##### d

#### Returns

[`PinInChat`](PinInChat.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10351)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10349)

#### Parameters

##### m

[`PinInChat`](PinInChat.md)

##### o?

`IConversionOptions`

#### Returns

`object`
