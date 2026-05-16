# Class: TapLinkAction

Defined in: [WAProto/index.d.ts:13159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13159)

## Implements

- [`ITapLinkAction`](../interfaces/ITapLinkAction.md)

## Constructors

### new TapLinkAction()

> **new TapLinkAction**(`p`?): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:13160](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13160)

#### Parameters

##### p?

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

#### Returns

[`TapLinkAction`](TapLinkAction.md)

## Properties

### tapUrl?

> `optional` **tapUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13162](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13162)

#### Implementation of

[`ITapLinkAction`](../interfaces/ITapLinkAction.md).[`tapUrl`](../interfaces/ITapLinkAction.md#tapurl)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:13161](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13161)

#### Implementation of

[`ITapLinkAction`](../interfaces/ITapLinkAction.md).[`title`](../interfaces/ITapLinkAction.md#title)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13168](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13168)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:13163](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13163)

#### Parameters

##### properties?

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

#### Returns

[`TapLinkAction`](TapLinkAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:13165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13165)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`TapLinkAction`](TapLinkAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13164](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13164)

#### Parameters

##### m

[`ITapLinkAction`](../interfaces/ITapLinkAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`TapLinkAction`](TapLinkAction.md)

Defined in: [WAProto/index.d.ts:13166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13166)

#### Parameters

##### d

#### Returns

[`TapLinkAction`](TapLinkAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13169](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13169)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13167)

#### Parameters

##### m

[`TapLinkAction`](TapLinkAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
