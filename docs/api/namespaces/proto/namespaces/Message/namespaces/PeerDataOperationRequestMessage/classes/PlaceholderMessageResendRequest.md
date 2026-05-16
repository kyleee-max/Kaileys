# Class: PlaceholderMessageResendRequest

Defined in: [WAProto/index.d.ts:7874](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7874)

## Implements

- [`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

## Constructors

### new PlaceholderMessageResendRequest()

> **new PlaceholderMessageResendRequest**(`p`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:7875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7875)

#### Parameters

##### p?

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

## Properties

### messageKey?

> `optional` **messageKey**: `null` \| [`IMessageKey`](../../../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:7876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7876)

#### Implementation of

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md).[`messageKey`](../interfaces/IPlaceholderMessageResendRequest.md#messagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7882](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7882)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:7877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7877)

#### Parameters

##### properties?

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:7879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7879)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7878)

#### Parameters

##### m

[`IPlaceholderMessageResendRequest`](../interfaces/IPlaceholderMessageResendRequest.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

Defined in: [WAProto/index.d.ts:7880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7880)

#### Parameters

##### d

#### Returns

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7883](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7883)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7881)

#### Parameters

##### m

[`PlaceholderMessageResendRequest`](PlaceholderMessageResendRequest.md)

##### o?

`IConversionOptions`

#### Returns

`object`
