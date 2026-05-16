# Class: FourRowTemplate

Defined in: [WAProto/index.d.ts:9222](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9222)

## Implements

- [`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

## Constructors

### new FourRowTemplate()

> **new FourRowTemplate**(`p`?): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9223](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9223)

#### Parameters

##### p?

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

## Properties

### buttons

> **buttons**: [`ITemplateButton`](../../../../../interfaces/ITemplateButton.md)[]

Defined in: [WAProto/index.d.ts:9226](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9226)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`buttons`](../interfaces/IFourRowTemplate.md#buttons)

***

### content?

> `optional` **content**: `null` \| [`IHighlyStructuredMessage`](../../../interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:9224](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9224)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`content`](../interfaces/IFourRowTemplate.md#content)

***

### documentMessage?

> `optional` **documentMessage**: `null` \| [`IDocumentMessage`](../../../interfaces/IDocumentMessage.md)

Defined in: [WAProto/index.d.ts:9227](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9227)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`documentMessage`](../interfaces/IFourRowTemplate.md#documentmessage)

***

### footer?

> `optional` **footer**: `null` \| [`IHighlyStructuredMessage`](../../../interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:9225](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9225)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`footer`](../interfaces/IFourRowTemplate.md#footer)

***

### highlyStructuredMessage?

> `optional` **highlyStructuredMessage**: `null` \| [`IHighlyStructuredMessage`](../../../interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:9228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9228)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`highlyStructuredMessage`](../interfaces/IFourRowTemplate.md#highlystructuredmessage)

***

### imageMessage?

> `optional` **imageMessage**: `null` \| [`IImageMessage`](../../../interfaces/IImageMessage.md)

Defined in: [WAProto/index.d.ts:9229](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9229)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`imageMessage`](../interfaces/IFourRowTemplate.md#imagemessage)

***

### locationMessage?

> `optional` **locationMessage**: `null` \| [`ILocationMessage`](../../../interfaces/ILocationMessage.md)

Defined in: [WAProto/index.d.ts:9231](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9231)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`locationMessage`](../interfaces/IFourRowTemplate.md#locationmessage)

***

### title?

> `optional` **title**: `"imageMessage"` \| `"locationMessage"` \| `"documentMessage"` \| `"videoMessage"` \| `"highlyStructuredMessage"`

Defined in: [WAProto/index.d.ts:9232](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9232)

***

### videoMessage?

> `optional` **videoMessage**: `null` \| [`IVideoMessage`](../../../interfaces/IVideoMessage.md)

Defined in: [WAProto/index.d.ts:9230](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9230)

#### Implementation of

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md).[`videoMessage`](../interfaces/IFourRowTemplate.md#videomessage)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9238](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9238)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9233](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9233)

#### Parameters

##### properties?

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9235](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9235)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9234](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9234)

#### Parameters

##### m

[`IFourRowTemplate`](../interfaces/IFourRowTemplate.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`FourRowTemplate`](FourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9236](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9236)

#### Parameters

##### d

#### Returns

[`FourRowTemplate`](FourRowTemplate.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9239](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9239)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9237](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9237)

#### Parameters

##### m

[`FourRowTemplate`](FourRowTemplate.md)

##### o?

`IConversionOptions`

#### Returns

`object`
