# Class: StatusStickerInteractionMessage

Defined in: [WAProto/index.d.ts:8967](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8967)

## Implements

- [`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md)

## Constructors

### new StatusStickerInteractionMessage()

> **new StatusStickerInteractionMessage**(`p`?): [`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

Defined in: [WAProto/index.d.ts:8968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8968)

#### Parameters

##### p?

[`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md)

#### Returns

[`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

## Properties

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8969)

#### Implementation of

[`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md).[`key`](../interfaces/IStatusStickerInteractionMessage.md#key)

***

### stickerKey?

> `optional` **stickerKey**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8970)

#### Implementation of

[`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md).[`stickerKey`](../interfaces/IStatusStickerInteractionMessage.md#stickerkey)

***

### type?

> `optional` **type**: `null` \| [`StatusStickerType`](../namespaces/StatusStickerInteractionMessage/enumerations/StatusStickerType.md)

Defined in: [WAProto/index.d.ts:8971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8971)

#### Implementation of

[`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md).[`type`](../interfaces/IStatusStickerInteractionMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8977](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8977)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

Defined in: [WAProto/index.d.ts:8972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8972)

#### Parameters

##### properties?

[`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md)

#### Returns

[`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

Defined in: [WAProto/index.d.ts:8974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8974)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8973)

#### Parameters

##### m

[`IStatusStickerInteractionMessage`](../interfaces/IStatusStickerInteractionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

Defined in: [WAProto/index.d.ts:8975](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8975)

#### Parameters

##### d

#### Returns

[`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8978](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8978)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8976](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8976)

#### Parameters

##### m

[`StatusStickerInteractionMessage`](StatusStickerInteractionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
