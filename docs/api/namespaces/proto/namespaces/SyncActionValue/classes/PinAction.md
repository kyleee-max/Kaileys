# Class: PinAction

Defined in: [WAProto/index.d.ts:12497](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12497)

## Implements

- [`IPinAction`](../interfaces/IPinAction.md)

## Constructors

### new PinAction()

> **new PinAction**(`p`?): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:12498](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12498)

#### Parameters

##### p?

[`IPinAction`](../interfaces/IPinAction.md)

#### Returns

[`PinAction`](PinAction.md)

## Properties

### pinned?

> `optional` **pinned**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12499](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12499)

#### Implementation of

[`IPinAction`](../interfaces/IPinAction.md).[`pinned`](../interfaces/IPinAction.md#pinned)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12505](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12505)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:12500](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12500)

#### Parameters

##### properties?

[`IPinAction`](../interfaces/IPinAction.md)

#### Returns

[`PinAction`](PinAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:12502](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12502)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PinAction`](PinAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12501](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12501)

#### Parameters

##### m

[`IPinAction`](../interfaces/IPinAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PinAction`](PinAction.md)

Defined in: [WAProto/index.d.ts:12503](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12503)

#### Parameters

##### d

#### Returns

[`PinAction`](PinAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12506](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12506)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12504](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12504)

#### Parameters

##### m

[`PinAction`](PinAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
