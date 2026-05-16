# Class: Button

Defined in: [WAProto/index.d.ts:5658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5658)

## Implements

- [`IButton`](../interfaces/IButton.md)

## Constructors

### new Button()

> **new Button**(`p`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:5659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5659)

#### Parameters

##### p?

[`IButton`](../interfaces/IButton.md)

#### Returns

[`Button`](Button.md)

## Properties

### buttonId?

> `optional` **buttonId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5660)

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`buttonId`](../interfaces/IButton.md#buttonid)

***

### buttonText?

> `optional` **buttonText**: `null` \| [`IButtonText`](../namespaces/Button/interfaces/IButtonText.md)

Defined in: [WAProto/index.d.ts:5661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5661)

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`buttonText`](../interfaces/IButton.md#buttontext)

***

### nativeFlowInfo?

> `optional` **nativeFlowInfo**: `null` \| [`INativeFlowInfo`](../namespaces/Button/interfaces/INativeFlowInfo.md)

Defined in: [WAProto/index.d.ts:5663](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5663)

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`nativeFlowInfo`](../interfaces/IButton.md#nativeflowinfo)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/Button/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:5662](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5662)

#### Implementation of

[`IButton`](../interfaces/IButton.md).[`type`](../interfaces/IButton.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5669](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5669)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:5664](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5664)

#### Parameters

##### properties?

[`IButton`](../interfaces/IButton.md)

#### Returns

[`Button`](Button.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:5666](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5666)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Button`](Button.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5665](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5665)

#### Parameters

##### m

[`IButton`](../interfaces/IButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Button`](Button.md)

Defined in: [WAProto/index.d.ts:5667](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5667)

#### Parameters

##### d

#### Returns

[`Button`](Button.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5670](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5670)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5668](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5668)

#### Parameters

##### m

[`Button`](Button.md)

##### o?

`IConversionOptions`

#### Returns

`object`
