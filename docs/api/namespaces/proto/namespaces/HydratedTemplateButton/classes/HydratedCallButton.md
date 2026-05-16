# Class: HydratedCallButton

Defined in: [WAProto/index.d.ts:4631](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4631)

## Implements

- [`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

## Constructors

### new HydratedCallButton()

> **new HydratedCallButton**(`p`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:4632](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4632)

#### Parameters

##### p?

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

## Properties

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4633](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4633)

#### Implementation of

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md).[`displayText`](../interfaces/IHydratedCallButton.md#displaytext)

***

### phoneNumber?

> `optional` **phoneNumber**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4634](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4634)

#### Implementation of

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md).[`phoneNumber`](../interfaces/IHydratedCallButton.md#phonenumber)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4640](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4640)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:4635](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4635)

#### Parameters

##### properties?

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:4637](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4637)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4636](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4636)

#### Parameters

##### m

[`IHydratedCallButton`](../interfaces/IHydratedCallButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HydratedCallButton`](HydratedCallButton.md)

Defined in: [WAProto/index.d.ts:4638](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4638)

#### Parameters

##### d

#### Returns

[`HydratedCallButton`](HydratedCallButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4641)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4639](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4639)

#### Parameters

##### m

[`HydratedCallButton`](HydratedCallButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
