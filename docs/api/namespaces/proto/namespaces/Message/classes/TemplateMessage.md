# Class: TemplateMessage

Defined in: [WAProto/index.d.ts:9191](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9191)

## Implements

- [`ITemplateMessage`](../interfaces/ITemplateMessage.md)

## Constructors

### new TemplateMessage()

> **new TemplateMessage**(`p`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:9192](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9192)

#### Parameters

##### p?

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

#### Returns

[`TemplateMessage`](TemplateMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:9193](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9193)

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`contextInfo`](../interfaces/ITemplateMessage.md#contextinfo)

***

### format?

> `optional` **format**: `"hydratedFourRowTemplate"` \| `"fourRowTemplate"` \| `"interactiveMessageTemplate"`

Defined in: [WAProto/index.d.ts:9199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9199)

***

### fourRowTemplate?

> `optional` **fourRowTemplate**: `null` \| [`IFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9196)

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`fourRowTemplate`](../interfaces/ITemplateMessage.md#fourrowtemplate)

***

### hydratedFourRowTemplate?

> `optional` **hydratedFourRowTemplate**: `null` \| [`IHydratedFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IHydratedFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9197)

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`hydratedFourRowTemplate`](../interfaces/ITemplateMessage.md#hydratedfourrowtemplate)

***

### hydratedTemplate?

> `optional` **hydratedTemplate**: `null` \| [`IHydratedFourRowTemplate`](../namespaces/TemplateMessage/interfaces/IHydratedFourRowTemplate.md)

Defined in: [WAProto/index.d.ts:9194](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9194)

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`hydratedTemplate`](../interfaces/ITemplateMessage.md#hydratedtemplate)

***

### interactiveMessageTemplate?

> `optional` **interactiveMessageTemplate**: `null` \| [`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

Defined in: [WAProto/index.d.ts:9198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9198)

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`interactiveMessageTemplate`](../interfaces/ITemplateMessage.md#interactivemessagetemplate)

***

### templateId?

> `optional` **templateId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:9195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9195)

#### Implementation of

[`ITemplateMessage`](../interfaces/ITemplateMessage.md).[`templateId`](../interfaces/ITemplateMessage.md#templateid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9205)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:9200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9200)

#### Parameters

##### properties?

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

#### Returns

[`TemplateMessage`](TemplateMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:9202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9202)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`TemplateMessage`](TemplateMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9201)

#### Parameters

##### m

[`ITemplateMessage`](../interfaces/ITemplateMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`TemplateMessage`](TemplateMessage.md)

Defined in: [WAProto/index.d.ts:9203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9203)

#### Parameters

##### d

#### Returns

[`TemplateMessage`](TemplateMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9206)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9204)

#### Parameters

##### m

[`TemplateMessage`](TemplateMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
