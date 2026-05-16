# Class: LabelReorderingAction

Defined in: [WAProto/index.d.ts:12136](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12136)

## Implements

- [`ILabelReorderingAction`](../interfaces/ILabelReorderingAction.md)

## Constructors

### new LabelReorderingAction()

> **new LabelReorderingAction**(`p`?): [`LabelReorderingAction`](LabelReorderingAction.md)

Defined in: [WAProto/index.d.ts:12137](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12137)

#### Parameters

##### p?

[`ILabelReorderingAction`](../interfaces/ILabelReorderingAction.md)

#### Returns

[`LabelReorderingAction`](LabelReorderingAction.md)

## Properties

### sortedLabelIds

> **sortedLabelIds**: `number`[]

Defined in: [WAProto/index.d.ts:12138](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12138)

#### Implementation of

[`ILabelReorderingAction`](../interfaces/ILabelReorderingAction.md).[`sortedLabelIds`](../interfaces/ILabelReorderingAction.md#sortedlabelids)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12144](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12144)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LabelReorderingAction`](LabelReorderingAction.md)

Defined in: [WAProto/index.d.ts:12139](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12139)

#### Parameters

##### properties?

[`ILabelReorderingAction`](../interfaces/ILabelReorderingAction.md)

#### Returns

[`LabelReorderingAction`](LabelReorderingAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LabelReorderingAction`](LabelReorderingAction.md)

Defined in: [WAProto/index.d.ts:12141](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12141)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LabelReorderingAction`](LabelReorderingAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12140](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12140)

#### Parameters

##### m

[`ILabelReorderingAction`](../interfaces/ILabelReorderingAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LabelReorderingAction`](LabelReorderingAction.md)

Defined in: [WAProto/index.d.ts:12142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12142)

#### Parameters

##### d

#### Returns

[`LabelReorderingAction`](LabelReorderingAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12145](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12145)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12143](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12143)

#### Parameters

##### m

[`LabelReorderingAction`](LabelReorderingAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
