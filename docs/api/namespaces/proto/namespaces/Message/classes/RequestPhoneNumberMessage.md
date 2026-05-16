# Class: RequestPhoneNumberMessage

Defined in: [WAProto/index.d.ts:8722](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8722)

## Implements

- [`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

## Constructors

### new RequestPhoneNumberMessage()

> **new RequestPhoneNumberMessage**(`p`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:8723](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8723)

#### Parameters

##### p?

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:8724](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8724)

#### Implementation of

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md).[`contextInfo`](../interfaces/IRequestPhoneNumberMessage.md#contextinfo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8730](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8730)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:8725](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8725)

#### Parameters

##### properties?

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:8727](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8727)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8726](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8726)

#### Parameters

##### m

[`IRequestPhoneNumberMessage`](../interfaces/IRequestPhoneNumberMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

Defined in: [WAProto/index.d.ts:8728](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8728)

#### Parameters

##### d

#### Returns

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8731](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8731)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8729](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8729)

#### Parameters

##### m

[`RequestPhoneNumberMessage`](RequestPhoneNumberMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
