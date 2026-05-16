# Class: EventResponseMessage

Defined in: [WAProto/index.d.ts:6195](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6195)

## Implements

- [`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

## Constructors

### new EventResponseMessage()

> **new EventResponseMessage**(`p`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6196](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6196)

#### Parameters

##### p?

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

## Properties

### extraGuestCount?

> `optional` **extraGuestCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:6199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6199)

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`extraGuestCount`](../interfaces/IEventResponseMessage.md#extraguestcount)

***

### response?

> `optional` **response**: `null` \| [`EventResponseType`](../namespaces/EventResponseMessage/enumerations/EventResponseType.md)

Defined in: [WAProto/index.d.ts:6197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6197)

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`response`](../interfaces/IEventResponseMessage.md#response)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:6198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6198)

#### Implementation of

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md).[`timestampMs`](../interfaces/IEventResponseMessage.md#timestampms)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6205)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6200)

#### Parameters

##### properties?

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6202)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6201)

#### Parameters

##### m

[`IEventResponseMessage`](../interfaces/IEventResponseMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EventResponseMessage`](EventResponseMessage.md)

Defined in: [WAProto/index.d.ts:6203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6203)

#### Parameters

##### d

#### Returns

[`EventResponseMessage`](EventResponseMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6206)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6204)

#### Parameters

##### m

[`EventResponseMessage`](EventResponseMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
