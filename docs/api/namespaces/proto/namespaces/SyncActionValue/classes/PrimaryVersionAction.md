# Class: PrimaryVersionAction

Defined in: [WAProto/index.d.ts:12545](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12545)

## Implements

- [`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

## Constructors

### new PrimaryVersionAction()

> **new PrimaryVersionAction**(`p`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:12546](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12546)

#### Parameters

##### p?

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

## Properties

### version?

> `optional` **version**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12547](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12547)

#### Implementation of

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md).[`version`](../interfaces/IPrimaryVersionAction.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12553](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12553)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:12548](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12548)

#### Parameters

##### properties?

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:12550](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12550)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12549](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12549)

#### Parameters

##### m

[`IPrimaryVersionAction`](../interfaces/IPrimaryVersionAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PrimaryVersionAction`](PrimaryVersionAction.md)

Defined in: [WAProto/index.d.ts:12551](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12551)

#### Parameters

##### d

#### Returns

[`PrimaryVersionAction`](PrimaryVersionAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12554](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12554)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12552](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12552)

#### Parameters

##### m

[`PrimaryVersionAction`](PrimaryVersionAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
