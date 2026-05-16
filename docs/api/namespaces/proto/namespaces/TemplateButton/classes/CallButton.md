# Class: CallButton

Defined in: [WAProto/index.d.ts:13202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13202)

## Implements

- [`ICallButton`](../interfaces/ICallButton.md)

## Constructors

### new CallButton()

> **new CallButton**(`p`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:13203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13203)

#### Parameters

##### p?

[`ICallButton`](../interfaces/ICallButton.md)

#### Returns

[`CallButton`](CallButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:13204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13204)

#### Implementation of

[`ICallButton`](../interfaces/ICallButton.md).[`displayText`](../interfaces/ICallButton.md#displaytext)

***

### phoneNumber?

> `optional` **phoneNumber**: `null` \| [`IHighlyStructuredMessage`](../../Message/interfaces/IHighlyStructuredMessage.md)

Defined in: [WAProto/index.d.ts:13205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13205)

#### Implementation of

[`ICallButton`](../interfaces/ICallButton.md).[`phoneNumber`](../interfaces/ICallButton.md#phonenumber)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13211](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13211)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:13206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13206)

#### Parameters

##### properties?

[`ICallButton`](../interfaces/ICallButton.md)

#### Returns

[`CallButton`](CallButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:13208](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13208)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CallButton`](CallButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13207](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13207)

#### Parameters

##### m

[`ICallButton`](../interfaces/ICallButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CallButton`](CallButton.md)

Defined in: [WAProto/index.d.ts:13209](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13209)

#### Parameters

##### d

#### Returns

[`CallButton`](CallButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13212](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13212)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13210](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13210)

#### Parameters

##### m

[`CallButton`](CallButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
