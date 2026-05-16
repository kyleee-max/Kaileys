# Class: NativeFlowButton

Defined in: [WAProto/index.d.ts:6913](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6913)

## Implements

- [`INativeFlowButton`](../interfaces/INativeFlowButton.md)

## Constructors

### new NativeFlowButton()

> **new NativeFlowButton**(`p`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:6914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6914)

#### Parameters

##### p?

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

## Properties

### buttonParamsJson?

> `optional` **buttonParamsJson**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6916](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6916)

#### Implementation of

[`INativeFlowButton`](../interfaces/INativeFlowButton.md).[`buttonParamsJson`](../interfaces/INativeFlowButton.md#buttonparamsjson)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6915](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6915)

#### Implementation of

[`INativeFlowButton`](../interfaces/INativeFlowButton.md).[`name`](../interfaces/INativeFlowButton.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6922](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6922)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:6917](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6917)

#### Parameters

##### properties?

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:6919](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6919)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6918](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6918)

#### Parameters

##### m

[`INativeFlowButton`](../interfaces/INativeFlowButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NativeFlowButton`](NativeFlowButton.md)

Defined in: [WAProto/index.d.ts:6920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6920)

#### Parameters

##### d

#### Returns

[`NativeFlowButton`](NativeFlowButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6923)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6921)

#### Parameters

##### m

[`NativeFlowButton`](NativeFlowButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
