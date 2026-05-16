# Class: ButtonsResponseMessage

Defined in: [WAProto/index.d.ts:5734](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5734)

## Implements

- [`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

## Constructors

### new ButtonsResponseMessage()

> **new ButtonsResponseMessage**(`p`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:5735](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5735)

#### Parameters

##### p?

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:5737](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5737)

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`contextInfo`](../interfaces/IButtonsResponseMessage.md#contextinfo)

***

### response?

> `optional` **response**: `"selectedDisplayText"`

Defined in: [WAProto/index.d.ts:5740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5740)

***

### selectedButtonId?

> `optional` **selectedButtonId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5736](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5736)

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`selectedButtonId`](../interfaces/IButtonsResponseMessage.md#selectedbuttonid)

***

### selectedDisplayText?

> `optional` **selectedDisplayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5739)

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`selectedDisplayText`](../interfaces/IButtonsResponseMessage.md#selecteddisplaytext)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/ButtonsResponseMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:5738](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5738)

#### Implementation of

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md).[`type`](../interfaces/IButtonsResponseMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5746)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:5741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5741)

#### Parameters

##### properties?

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:5743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5743)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5742)

#### Parameters

##### m

[`IButtonsResponseMessage`](../interfaces/IButtonsResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ButtonsResponseMessage`](ButtonsResponseMessage.md)

Defined in: [WAProto/index.d.ts:5744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5744)

#### Parameters

##### d

#### Returns

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5747)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5745)

#### Parameters

##### m

[`ButtonsResponseMessage`](ButtonsResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
