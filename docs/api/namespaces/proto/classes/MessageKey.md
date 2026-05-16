# Class: MessageKey

Defined in: [WAProto/index.d.ts:9574](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9574)

## Implements

- [`IMessageKey`](../interfaces/IMessageKey.md)

## Constructors

### new MessageKey()

> **new MessageKey**(`p`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:9575](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9575)

#### Parameters

##### p?

[`IMessageKey`](../interfaces/IMessageKey.md)

#### Returns

[`MessageKey`](MessageKey.md)

## Properties

### fromMe?

> `optional` **fromMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:9577](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9577)

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`fromMe`](../interfaces/IMessageKey.md#fromme)

***

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9578](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9578)

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`id`](../interfaces/IMessageKey.md#id)

***

### participant?

> `optional` **participant**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9579](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9579)

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`participant`](../interfaces/IMessageKey.md#participant)

***

### remoteJid?

> `optional` **remoteJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9576](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9576)

#### Implementation of

[`IMessageKey`](../interfaces/IMessageKey.md).[`remoteJid`](../interfaces/IMessageKey.md#remotejid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9585](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9585)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:9580](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9580)

#### Parameters

##### properties?

[`IMessageKey`](../interfaces/IMessageKey.md)

#### Returns

[`MessageKey`](MessageKey.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:9582](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9582)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageKey`](MessageKey.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9581](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9581)

#### Parameters

##### m

[`IMessageKey`](../interfaces/IMessageKey.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageKey`](MessageKey.md)

Defined in: [WAProto/index.d.ts:9583](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9583)

#### Parameters

##### d

#### Returns

[`MessageKey`](MessageKey.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9586](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9586)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9584](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9584)

#### Parameters

##### m

[`MessageKey`](MessageKey.md)

##### o?

`IConversionOptions`

#### Returns

`object`
