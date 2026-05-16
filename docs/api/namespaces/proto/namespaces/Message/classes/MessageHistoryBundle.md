# Class: MessageHistoryBundle

Defined in: [WAProto/index.d.ts:7452](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7452)

## Implements

- [`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

## Constructors

### new MessageHistoryBundle()

> **new MessageHistoryBundle**(`p`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:7453](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7453)

#### Parameters

##### p?

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7460](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7460)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`contextInfo`](../interfaces/IMessageHistoryBundle.md#contextinfo)

***

### directPath?

> `optional` **directPath**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7458](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7458)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`directPath`](../interfaces/IMessageHistoryBundle.md#directpath)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7457](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7457)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`fileEncSha256`](../interfaces/IMessageHistoryBundle.md#fileencsha256)

***

### fileSha256?

> `optional` **fileSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7455](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7455)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`fileSha256`](../interfaces/IMessageHistoryBundle.md#filesha256)

***

### mediaKey?

> `optional` **mediaKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7456](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7456)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mediaKey`](../interfaces/IMessageHistoryBundle.md#mediakey)

***

### mediaKeyTimestamp?

> `optional` **mediaKeyTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7459](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7459)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mediaKeyTimestamp`](../interfaces/IMessageHistoryBundle.md#mediakeytimestamp)

***

### messageHistoryMetadata?

> `optional` **messageHistoryMetadata**: `null` \| [`IMessageHistoryMetadata`](../interfaces/IMessageHistoryMetadata.md)

Defined in: [WAProto/index.d.ts:7461](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7461)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`messageHistoryMetadata`](../interfaces/IMessageHistoryBundle.md#messagehistorymetadata)

***

### mimetype?

> `optional` **mimetype**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7454](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7454)

#### Implementation of

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md).[`mimetype`](../interfaces/IMessageHistoryBundle.md#mimetype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7467](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7467)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:7462](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7462)

#### Parameters

##### properties?

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:7464](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7464)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7463](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7463)

#### Parameters

##### m

[`IMessageHistoryBundle`](../interfaces/IMessageHistoryBundle.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageHistoryBundle`](MessageHistoryBundle.md)

Defined in: [WAProto/index.d.ts:7465](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7465)

#### Parameters

##### d

#### Returns

[`MessageHistoryBundle`](MessageHistoryBundle.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7468](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7468)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7466](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7466)

#### Parameters

##### m

[`MessageHistoryBundle`](MessageHistoryBundle.md)

##### o?

`IConversionOptions`

#### Returns

`object`
