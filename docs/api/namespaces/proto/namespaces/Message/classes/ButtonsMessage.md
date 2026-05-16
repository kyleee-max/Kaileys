# Class: ButtonsMessage

Defined in: [WAProto/index.d.ts:5627](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5627)

## Implements

- [`IButtonsMessage`](../interfaces/IButtonsMessage.md)

## Constructors

### new ButtonsMessage()

> **new ButtonsMessage**(`p`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:5628](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5628)

#### Parameters

##### p?

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

## Properties

### buttons

> **buttons**: [`IButton`](../namespaces/ButtonsMessage/interfaces/IButton.md)[]

Defined in: [WAProto/index.d.ts:5632](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5632)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`buttons`](../interfaces/IButtonsMessage.md#buttons)

***

### contentText?

> `optional` **contentText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5629](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5629)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`contentText`](../interfaces/IButtonsMessage.md#contenttext)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:5631](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5631)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`contextInfo`](../interfaces/IButtonsMessage.md#contextinfo)

***

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:5635](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5635)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`documentMessage`](../interfaces/IButtonsMessage.md#documentmessage)

***

### footerText?

> `optional` **footerText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5630](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5630)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`footerText`](../interfaces/IButtonsMessage.md#footertext)

***

### header?

> `optional` **header**: `"text"` \| `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"`

Defined in: [WAProto/index.d.ts:5639](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5639)

***

### headerType?

> `optional` **headerType**: `null` \| [`HeaderType`](../namespaces/ButtonsMessage/enumerations/HeaderType.md)

Defined in: [WAProto/index.d.ts:5633](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5633)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`headerType`](../interfaces/IButtonsMessage.md#headertype)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:5636](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5636)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`imageMessage`](../interfaces/IButtonsMessage.md#imagemessage)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:5638](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5638)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`locationMessage`](../interfaces/IButtonsMessage.md#locationmessage)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5634](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5634)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`text`](../interfaces/IButtonsMessage.md#text)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:5637](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5637)

#### Implementation of

[`IButtonsMessage`](../interfaces/IButtonsMessage.md).[`videoMessage`](../interfaces/IButtonsMessage.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5645](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5645)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:5640](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5640)

#### Parameters

##### properties?

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:5642](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5642)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5641)

#### Parameters

##### m

[`IButtonsMessage`](../interfaces/IButtonsMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ButtonsMessage`](ButtonsMessage.md)

Defined in: [WAProto/index.d.ts:5643](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5643)

#### Parameters

##### d

#### Returns

[`ButtonsMessage`](ButtonsMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5646](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5646)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5644](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5644)

#### Parameters

##### m

[`ButtonsMessage`](ButtonsMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
