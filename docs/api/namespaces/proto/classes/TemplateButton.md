# Class: TemplateButton

Defined in: [WAProto/index.d.ts:13179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13179)

## Implements

- [`ITemplateButton`](../interfaces/ITemplateButton.md)

## Constructors

### new TemplateButton()

> **new TemplateButton**(`p`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:13180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13180)

#### Parameters

##### p?

[`ITemplateButton`](../interfaces/ITemplateButton.md)

#### Returns

[`TemplateButton`](TemplateButton.md)

## Properties

### button?

> `optional` **button**: `"quickReplyButton"` \| `"urlButton"` \| `"callButton"`

Defined in: [WAProto/index.d.ts:13185](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13185)

***

### callButton?

> `optional` **callButton**: `null` \| [`ICallButton`](../namespaces/TemplateButton/interfaces/ICallButton.md)

Defined in: [WAProto/index.d.ts:13184](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13184)

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`callButton`](../interfaces/ITemplateButton.md#callbutton)

***

### index?

> `optional` **index**: `null` \| `number`

Defined in: [WAProto/index.d.ts:13181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13181)

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`index`](../interfaces/ITemplateButton.md#index)

***

### quickReplyButton?

> `optional` **quickReplyButton**: `null` \| [`IQuickReplyButton`](../namespaces/TemplateButton/interfaces/IQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:13182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13182)

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`quickReplyButton`](../interfaces/ITemplateButton.md#quickreplybutton)

***

### urlButton?

> `optional` **urlButton**: `null` \| [`IURLButton`](../namespaces/TemplateButton/interfaces/IURLButton.md)

Defined in: [WAProto/index.d.ts:13183](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13183)

#### Implementation of

[`ITemplateButton`](../interfaces/ITemplateButton.md).[`urlButton`](../interfaces/ITemplateButton.md#urlbutton)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13191](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13191)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:13186](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13186)

#### Parameters

##### properties?

[`ITemplateButton`](../interfaces/ITemplateButton.md)

#### Returns

[`TemplateButton`](TemplateButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:13188](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13188)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`TemplateButton`](TemplateButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13187](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13187)

#### Parameters

##### m

[`ITemplateButton`](../interfaces/ITemplateButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`TemplateButton`](TemplateButton.md)

Defined in: [WAProto/index.d.ts:13189](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13189)

#### Parameters

##### d

#### Returns

[`TemplateButton`](TemplateButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13192](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13192)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13190](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13190)

#### Parameters

##### m

[`TemplateButton`](TemplateButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
