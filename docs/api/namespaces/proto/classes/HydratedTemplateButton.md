# Class: HydratedTemplateButton

Defined in: [WAProto/index.d.ts:4608](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4608)

## Implements

- [`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

## Constructors

### new HydratedTemplateButton()

> **new HydratedTemplateButton**(`p`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:4609](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4609)

#### Parameters

##### p?

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

## Properties

### callButton?

> `optional` **callButton**: `null` \| [`IHydratedCallButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedCallButton.md)

Defined in: [WAProto/index.d.ts:4613](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4613)

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`callButton`](../interfaces/IHydratedTemplateButton.md#callbutton)

***

### hydratedButton?

> `optional` **hydratedButton**: `"quickReplyButton"` \| `"urlButton"` \| `"callButton"`

Defined in: [WAProto/index.d.ts:4614](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4614)

***

### index?

> `optional` **index**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4610](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4610)

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`index`](../interfaces/IHydratedTemplateButton.md#index)

***

### quickReplyButton?

> `optional` **quickReplyButton**: `null` \| [`IHydratedQuickReplyButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedQuickReplyButton.md)

Defined in: [WAProto/index.d.ts:4611](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4611)

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`quickReplyButton`](../interfaces/IHydratedTemplateButton.md#quickreplybutton)

***

### urlButton?

> `optional` **urlButton**: `null` \| [`IHydratedURLButton`](../namespaces/HydratedTemplateButton/interfaces/IHydratedURLButton.md)

Defined in: [WAProto/index.d.ts:4612](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4612)

#### Implementation of

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md).[`urlButton`](../interfaces/IHydratedTemplateButton.md#urlbutton)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4620](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4620)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:4615](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4615)

#### Parameters

##### properties?

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:4617](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4617)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4616](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4616)

#### Parameters

##### m

[`IHydratedTemplateButton`](../interfaces/IHydratedTemplateButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HydratedTemplateButton`](HydratedTemplateButton.md)

Defined in: [WAProto/index.d.ts:4618](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4618)

#### Parameters

##### d

#### Returns

[`HydratedTemplateButton`](HydratedTemplateButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4621](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4621)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4619](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4619)

#### Parameters

##### m

[`HydratedTemplateButton`](HydratedTemplateButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
