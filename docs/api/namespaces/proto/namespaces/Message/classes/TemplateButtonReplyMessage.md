# Class: TemplateButtonReplyMessage

Defined in: [WAProto/index.d.ts:9166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9166)

## Implements

- [`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

## Constructors

### new TemplateButtonReplyMessage()

> **new TemplateButtonReplyMessage**(`p`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:9167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9167)

#### Parameters

##### p?

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:9170](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9170)

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`contextInfo`](../interfaces/ITemplateButtonReplyMessage.md#contextinfo)

***

### selectedCarouselCardIndex?

> `optional` **selectedCarouselCardIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9172](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9172)

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedCarouselCardIndex`](../interfaces/ITemplateButtonReplyMessage.md#selectedcarouselcardindex)

***

### selectedDisplayText?

> `optional` **selectedDisplayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9169](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9169)

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedDisplayText`](../interfaces/ITemplateButtonReplyMessage.md#selecteddisplaytext)

***

### selectedId?

> `optional` **selectedId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9168](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9168)

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedId`](../interfaces/ITemplateButtonReplyMessage.md#selectedid)

***

### selectedIndex?

> `optional` **selectedIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9171](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9171)

#### Implementation of

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md).[`selectedIndex`](../interfaces/ITemplateButtonReplyMessage.md#selectedindex)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9178)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:9173](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9173)

#### Parameters

##### properties?

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:9175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9175)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9174)

#### Parameters

##### m

[`ITemplateButtonReplyMessage`](../interfaces/ITemplateButtonReplyMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

Defined in: [WAProto/index.d.ts:9176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9176)

#### Parameters

##### d

#### Returns

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9179)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9177)

#### Parameters

##### m

[`TemplateButtonReplyMessage`](TemplateButtonReplyMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
