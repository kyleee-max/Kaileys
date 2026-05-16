# Class: EventResponse

Defined in: [WAProto/index.d.ts:4177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4177)

## Implements

- [`IEventResponse`](../interfaces/IEventResponse.md)

## Constructors

### new EventResponse()

> **new EventResponse**(`p`?): [`EventResponse`](EventResponse.md)

Defined in: [WAProto/index.d.ts:4178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4178)

#### Parameters

##### p?

[`IEventResponse`](../interfaces/IEventResponse.md)

#### Returns

[`EventResponse`](EventResponse.md)

## Properties

### eventResponseMessage?

> `optional` **eventResponseMessage**: `null` \| [`IEventResponseMessage`](../namespaces/Message/interfaces/IEventResponseMessage.md)

Defined in: [WAProto/index.d.ts:4181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4181)

#### Implementation of

[`IEventResponse`](../interfaces/IEventResponse.md).[`eventResponseMessage`](../interfaces/IEventResponse.md#eventresponsemessage)

***

### eventResponseMessageKey?

> `optional` **eventResponseMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:4179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4179)

#### Implementation of

[`IEventResponse`](../interfaces/IEventResponse.md).[`eventResponseMessageKey`](../interfaces/IEventResponse.md#eventresponsemessagekey)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4180)

#### Implementation of

[`IEventResponse`](../interfaces/IEventResponse.md).[`timestampMs`](../interfaces/IEventResponse.md#timestampms)

***

### unread?

> `optional` **unread**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4182)

#### Implementation of

[`IEventResponse`](../interfaces/IEventResponse.md).[`unread`](../interfaces/IEventResponse.md#unread)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4188](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4188)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`EventResponse`](EventResponse.md)

Defined in: [WAProto/index.d.ts:4183](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4183)

#### Parameters

##### properties?

[`IEventResponse`](../interfaces/IEventResponse.md)

#### Returns

[`EventResponse`](EventResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`EventResponse`](EventResponse.md)

Defined in: [WAProto/index.d.ts:4185](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4185)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`EventResponse`](EventResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4184](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4184)

#### Parameters

##### m

[`IEventResponse`](../interfaces/IEventResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`EventResponse`](EventResponse.md)

Defined in: [WAProto/index.d.ts:4186](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4186)

#### Parameters

##### d

#### Returns

[`EventResponse`](EventResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4189](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4189)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4187](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4187)

#### Parameters

##### m

[`EventResponse`](EventResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
