# Class: RequestPaymentMessage

Defined in: [WAProto/index.d.ts:8700](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8700)

## Implements

- [`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

## Constructors

### new RequestPaymentMessage()

> **new RequestPaymentMessage**(`p`?): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8701](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8701)

#### Parameters

##### p?

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

## Properties

### amount?

> `optional` **amount**: `null` \| [`IMoney`](../../../interfaces/IMoney.md)

Defined in: [WAProto/index.d.ts:8707](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8707)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`amount`](../interfaces/IRequestPaymentMessage.md#amount)

***

### amount1000?

> `optional` **amount1000**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8704](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8704)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`amount1000`](../interfaces/IRequestPaymentMessage.md#amount1000)

***

### background?

> `optional` **background**: `null` \| [`IPaymentBackground`](../../../interfaces/IPaymentBackground.md)

Defined in: [WAProto/index.d.ts:8708](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8708)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`background`](../interfaces/IRequestPaymentMessage.md#background)

***

### currencyCodeIso4217?

> `optional` **currencyCodeIso4217**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8703](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8703)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`currencyCodeIso4217`](../interfaces/IRequestPaymentMessage.md#currencycodeiso4217)

***

### expiryTimestamp?

> `optional` **expiryTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8706](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8706)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`expiryTimestamp`](../interfaces/IRequestPaymentMessage.md#expirytimestamp)

***

### noteMessage?

> `optional` **noteMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:8702](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8702)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`noteMessage`](../interfaces/IRequestPaymentMessage.md#notemessage)

***

### requestFrom?

> `optional` **requestFrom**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8705](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8705)

#### Implementation of

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md).[`requestFrom`](../interfaces/IRequestPaymentMessage.md#requestfrom)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8714](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8714)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8709](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8709)

#### Parameters

##### properties?

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8711](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8711)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8710](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8710)

#### Parameters

##### m

[`IRequestPaymentMessage`](../interfaces/IRequestPaymentMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RequestPaymentMessage`](RequestPaymentMessage.md)

Defined in: [WAProto/index.d.ts:8712](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8712)

#### Parameters

##### d

#### Returns

[`RequestPaymentMessage`](RequestPaymentMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8715](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8715)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8713](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8713)

#### Parameters

##### m

[`RequestPaymentMessage`](RequestPaymentMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
