# Class: BCallMessage

Defined in: [WAProto/index.d.ts:5590](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5590)

## Implements

- [`IBCallMessage`](../interfaces/IBCallMessage.md)

## Constructors

### new BCallMessage()

> **new BCallMessage**(`p`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:5591](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5591)

#### Parameters

##### p?

[`IBCallMessage`](../interfaces/IBCallMessage.md)

#### Returns

[`BCallMessage`](BCallMessage.md)

## Properties

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5595)

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`caption`](../interfaces/IBCallMessage.md#caption)

***

### masterKey?

> `optional` **masterKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5594)

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`masterKey`](../interfaces/IBCallMessage.md#masterkey)

***

### mediaType?

> `optional` **mediaType**: `null` \| [`MediaType`](../namespaces/BCallMessage/enumerations/MediaType.md)

Defined in: [WAProto/index.d.ts:5593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5593)

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`mediaType`](../interfaces/IBCallMessage.md#mediatype)

***

### sessionId?

> `optional` **sessionId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5592)

#### Implementation of

[`IBCallMessage`](../interfaces/IBCallMessage.md).[`sessionId`](../interfaces/IBCallMessage.md#sessionid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5601](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5601)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:5596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5596)

#### Parameters

##### properties?

[`IBCallMessage`](../interfaces/IBCallMessage.md)

#### Returns

[`BCallMessage`](BCallMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:5598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5598)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BCallMessage`](BCallMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5597)

#### Parameters

##### m

[`IBCallMessage`](../interfaces/IBCallMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BCallMessage`](BCallMessage.md)

Defined in: [WAProto/index.d.ts:5599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5599)

#### Parameters

##### d

#### Returns

[`BCallMessage`](BCallMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5602](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5602)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5600)

#### Parameters

##### m

[`BCallMessage`](BCallMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
