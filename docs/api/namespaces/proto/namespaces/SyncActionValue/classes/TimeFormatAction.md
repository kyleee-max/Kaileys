# Class: TimeFormatAction

Defined in: [WAProto/index.d.ts:12864](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12864)

## Implements

- [`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

## Constructors

### new TimeFormatAction()

> **new TimeFormatAction**(`p`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:12865](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12865)

#### Parameters

##### p?

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

## Properties

### isTwentyFourHourFormatEnabled?

> `optional` **isTwentyFourHourFormatEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12866](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12866)

#### Implementation of

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md).[`isTwentyFourHourFormatEnabled`](../interfaces/ITimeFormatAction.md#istwentyfourhourformatenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12872](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12872)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:12867](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12867)

#### Parameters

##### properties?

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:12869](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12869)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12868](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12868)

#### Parameters

##### m

[`ITimeFormatAction`](../interfaces/ITimeFormatAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`TimeFormatAction`](TimeFormatAction.md)

Defined in: [WAProto/index.d.ts:12870](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12870)

#### Parameters

##### d

#### Returns

[`TimeFormatAction`](TimeFormatAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12873](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12873)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12871](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12871)

#### Parameters

##### m

[`TimeFormatAction`](TimeFormatAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
