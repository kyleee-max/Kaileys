# Class: ButtonText

Defined in: [WAProto/index.d.ts:5679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5679)

## Implements

- [`IButtonText`](../interfaces/IButtonText.md)

## Constructors

### new ButtonText()

> **new ButtonText**(`p`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:5680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5680)

#### Parameters

##### p?

[`IButtonText`](../interfaces/IButtonText.md)

#### Returns

[`ButtonText`](ButtonText.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5681)

#### Implementation of

[`IButtonText`](../interfaces/IButtonText.md).[`displayText`](../interfaces/IButtonText.md#displaytext)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5687](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5687)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:5682](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5682)

#### Parameters

##### properties?

[`IButtonText`](../interfaces/IButtonText.md)

#### Returns

[`ButtonText`](ButtonText.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:5684](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5684)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ButtonText`](ButtonText.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5683](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5683)

#### Parameters

##### m

[`IButtonText`](../interfaces/IButtonText.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ButtonText`](ButtonText.md)

Defined in: [WAProto/index.d.ts:5685](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5685)

#### Parameters

##### d

#### Returns

[`ButtonText`](ButtonText.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5688](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5688)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5686](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5686)

#### Parameters

##### m

[`ButtonText`](ButtonText.md)

##### o?

`IConversionOptions`

#### Returns

`object`
