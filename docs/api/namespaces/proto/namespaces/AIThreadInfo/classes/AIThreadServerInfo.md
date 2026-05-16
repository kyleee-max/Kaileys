# Class: AIThreadServerInfo

Defined in: [WAProto/index.d.ts:716](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L716)

## Implements

- [`IAIThreadServerInfo`](../interfaces/IAIThreadServerInfo.md)

## Constructors

### new AIThreadServerInfo()

> **new AIThreadServerInfo**(`p`?): [`AIThreadServerInfo`](AIThreadServerInfo.md)

Defined in: [WAProto/index.d.ts:717](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L717)

#### Parameters

##### p?

[`IAIThreadServerInfo`](../interfaces/IAIThreadServerInfo.md)

#### Returns

[`AIThreadServerInfo`](AIThreadServerInfo.md)

## Properties

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:718](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L718)

#### Implementation of

[`IAIThreadServerInfo`](../interfaces/IAIThreadServerInfo.md).[`title`](../interfaces/IAIThreadServerInfo.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:724](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L724)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIThreadServerInfo`](AIThreadServerInfo.md)

Defined in: [WAProto/index.d.ts:719](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L719)

#### Parameters

##### properties?

[`IAIThreadServerInfo`](../interfaces/IAIThreadServerInfo.md)

#### Returns

[`AIThreadServerInfo`](AIThreadServerInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIThreadServerInfo`](AIThreadServerInfo.md)

Defined in: [WAProto/index.d.ts:721](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L721)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIThreadServerInfo`](AIThreadServerInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:720](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L720)

#### Parameters

##### m

[`IAIThreadServerInfo`](../interfaces/IAIThreadServerInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIThreadServerInfo`](AIThreadServerInfo.md)

Defined in: [WAProto/index.d.ts:722](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L722)

#### Parameters

##### d

#### Returns

[`AIThreadServerInfo`](AIThreadServerInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:725](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L725)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:723](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L723)

#### Parameters

##### m

[`AIThreadServerInfo`](AIThreadServerInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
