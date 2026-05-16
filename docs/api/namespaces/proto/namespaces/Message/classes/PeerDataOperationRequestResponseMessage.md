# Class: PeerDataOperationRequestResponseMessage

Defined in: [WAProto/index.d.ts:7945](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7945)

## Implements

- [`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

## Constructors

### new PeerDataOperationRequestResponseMessage()

> **new PeerDataOperationRequestResponseMessage**(`p`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:7946](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7946)

#### Parameters

##### p?

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

## Properties

### peerDataOperationRequestType?

> `optional` **peerDataOperationRequestType**: `null` \| [`PeerDataOperationRequestType`](../enumerations/PeerDataOperationRequestType.md)

Defined in: [WAProto/index.d.ts:7947](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7947)

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`peerDataOperationRequestType`](../interfaces/IPeerDataOperationRequestResponseMessage.md#peerdataoperationrequesttype)

***

### peerDataOperationResult

> **peerDataOperationResult**: [`IPeerDataOperationResult`](../namespaces/PeerDataOperationRequestResponseMessage/interfaces/IPeerDataOperationResult.md)[]

Defined in: [WAProto/index.d.ts:7949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7949)

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`peerDataOperationResult`](../interfaces/IPeerDataOperationRequestResponseMessage.md#peerdataoperationresult)

***

### stanzaId?

> `optional` **stanzaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7948](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7948)

#### Implementation of

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md).[`stanzaId`](../interfaces/IPeerDataOperationRequestResponseMessage.md#stanzaid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7955)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:7950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7950)

#### Parameters

##### properties?

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:7952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7952)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7951)

#### Parameters

##### m

[`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:7953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7953)

#### Parameters

##### d

#### Returns

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7956)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7954)

#### Parameters

##### m

[`PeerDataOperationRequestResponseMessage`](PeerDataOperationRequestResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
