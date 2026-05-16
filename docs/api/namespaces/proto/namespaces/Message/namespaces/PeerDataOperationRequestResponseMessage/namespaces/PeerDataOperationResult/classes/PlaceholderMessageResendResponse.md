# Class: PlaceholderMessageResendResponse

Defined in: [WAProto/index.d.ts:8177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8177)

## Implements

- [`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

## Constructors

### new PlaceholderMessageResendResponse()

> **new PlaceholderMessageResendResponse**(`p`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:8178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8178)

#### Parameters

##### p?

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

## Properties

### webMessageInfoBytes?

> `optional` **webMessageInfoBytes**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8179](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8179)

#### Implementation of

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md).[`webMessageInfoBytes`](../interfaces/IPlaceholderMessageResendResponse.md#webmessageinfobytes)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8185](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8185)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:8180](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8180)

#### Parameters

##### properties?

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:8182](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8182)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8181](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8181)

#### Parameters

##### m

[`IPlaceholderMessageResendResponse`](../interfaces/IPlaceholderMessageResendResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

Defined in: [WAProto/index.d.ts:8183](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8183)

#### Parameters

##### d

#### Returns

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8186](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8186)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8184](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8184)

#### Parameters

##### m

[`PlaceholderMessageResendResponse`](PlaceholderMessageResendResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
