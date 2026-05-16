# Class: Pushname

Defined in: [WAProto/index.d.ts:10592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10592)

## Implements

- [`IPushname`](../interfaces/IPushname.md)

## Constructors

### new Pushname()

> **new Pushname**(`p`?): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:10593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10593)

#### Parameters

##### p?

[`IPushname`](../interfaces/IPushname.md)

#### Returns

[`Pushname`](Pushname.md)

## Properties

### id?

> `optional` **id**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10594)

#### Implementation of

[`IPushname`](../interfaces/IPushname.md).[`id`](../interfaces/IPushname.md#id)

***

### pushname?

> `optional` **pushname**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10595)

#### Implementation of

[`IPushname`](../interfaces/IPushname.md).[`pushname`](../interfaces/IPushname.md#pushname)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10601](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10601)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:10596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10596)

#### Parameters

##### properties?

[`IPushname`](../interfaces/IPushname.md)

#### Returns

[`Pushname`](Pushname.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:10598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10598)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Pushname`](Pushname.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10597)

#### Parameters

##### m

[`IPushname`](../interfaces/IPushname.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Pushname`](Pushname.md)

Defined in: [WAProto/index.d.ts:10599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10599)

#### Parameters

##### d

#### Returns

[`Pushname`](Pushname.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10602](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10602)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10600)

#### Parameters

##### m

[`Pushname`](Pushname.md)

##### o?

`IConversionOptions`

#### Returns

`object`
