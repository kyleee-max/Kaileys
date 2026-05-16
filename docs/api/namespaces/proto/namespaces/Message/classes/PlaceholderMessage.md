# Class: PlaceholderMessage

Defined in: [WAProto/index.d.ts:8275](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8275)

## Implements

- [`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

## Constructors

### new PlaceholderMessage()

> **new PlaceholderMessage**(`p`?): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:8276](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8276)

#### Parameters

##### p?

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

## Properties

### type?

> `optional` **type**: `null` \| [`MASK_LINKED_DEVICES`](../namespaces/PlaceholderMessage/enumerations/PlaceholderType.md#mask_linked_devices)

Defined in: [WAProto/index.d.ts:8277](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8277)

#### Implementation of

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md).[`type`](../interfaces/IPlaceholderMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8283](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8283)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:8278](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8278)

#### Parameters

##### properties?

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:8280](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8280)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8279](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8279)

#### Parameters

##### m

[`IPlaceholderMessage`](../interfaces/IPlaceholderMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PlaceholderMessage`](PlaceholderMessage.md)

Defined in: [WAProto/index.d.ts:8281](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8281)

#### Parameters

##### d

#### Returns

[`PlaceholderMessage`](PlaceholderMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8284](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8284)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8282](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8282)

#### Parameters

##### m

[`PlaceholderMessage`](PlaceholderMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
