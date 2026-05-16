# Class: MessageAddOn

Defined in: [WAProto/index.d.ts:9419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9419)

## Implements

- [`IMessageAddOn`](../interfaces/IMessageAddOn.md)

## Constructors

### new MessageAddOn()

> **new MessageAddOn**(`p`?): [`MessageAddOn`](MessageAddOn.md)

Defined in: [WAProto/index.d.ts:9420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9420)

#### Parameters

##### p?

[`IMessageAddOn`](../interfaces/IMessageAddOn.md)

#### Returns

[`MessageAddOn`](MessageAddOn.md)

## Properties

### addOnContextInfo?

> `optional` **addOnContextInfo**: `null` \| [`IMessageAddOnContextInfo`](../interfaces/IMessageAddOnContextInfo.md)

Defined in: [WAProto/index.d.ts:9426](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9426)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`addOnContextInfo`](../interfaces/IMessageAddOn.md#addoncontextinfo)

***

### legacyMessage?

> `optional` **legacyMessage**: `null` \| [`ILegacyMessage`](../interfaces/ILegacyMessage.md)

Defined in: [WAProto/index.d.ts:9428](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9428)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`legacyMessage`](../interfaces/IMessageAddOn.md#legacymessage)

***

### messageAddOn?

> `optional` **messageAddOn**: `null` \| [`IMessage`](../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:9422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9422)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`messageAddOn`](../interfaces/IMessageAddOn.md#messageaddon)

***

### messageAddOnKey?

> `optional` **messageAddOnKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:9427](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9427)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`messageAddOnKey`](../interfaces/IMessageAddOn.md#messageaddonkey)

***

### messageAddOnType?

> `optional` **messageAddOnType**: `null` \| [`MessageAddOnType`](../namespaces/MessageAddOn/enumerations/MessageAddOnType.md)

Defined in: [WAProto/index.d.ts:9421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9421)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`messageAddOnType`](../interfaces/IMessageAddOn.md#messageaddontype)

***

### senderTimestampMs?

> `optional` **senderTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9423)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`senderTimestampMs`](../interfaces/IMessageAddOn.md#sendertimestampms)

***

### serverTimestampMs?

> `optional` **serverTimestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:9424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9424)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`serverTimestampMs`](../interfaces/IMessageAddOn.md#servertimestampms)

***

### status?

> `optional` **status**: `null` \| [`Status`](../namespaces/WebMessageInfo/enumerations/Status.md)

Defined in: [WAProto/index.d.ts:9425](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9425)

#### Implementation of

[`IMessageAddOn`](../interfaces/IMessageAddOn.md).[`status`](../interfaces/IMessageAddOn.md#status)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9434](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9434)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageAddOn`](MessageAddOn.md)

Defined in: [WAProto/index.d.ts:9429](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9429)

#### Parameters

##### properties?

[`IMessageAddOn`](../interfaces/IMessageAddOn.md)

#### Returns

[`MessageAddOn`](MessageAddOn.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageAddOn`](MessageAddOn.md)

Defined in: [WAProto/index.d.ts:9431](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9431)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageAddOn`](MessageAddOn.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9430](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9430)

#### Parameters

##### m

[`IMessageAddOn`](../interfaces/IMessageAddOn.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageAddOn`](MessageAddOn.md)

Defined in: [WAProto/index.d.ts:9432](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9432)

#### Parameters

##### d

#### Returns

[`MessageAddOn`](MessageAddOn.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9435](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9435)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9433](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9433)

#### Parameters

##### m

[`MessageAddOn`](MessageAddOn.md)

##### o?

`IConversionOptions`

#### Returns

`object`
