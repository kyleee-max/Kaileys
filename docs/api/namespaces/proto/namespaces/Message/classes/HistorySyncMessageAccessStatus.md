# Class: HistorySyncMessageAccessStatus

Defined in: [WAProto/index.d.ts:6562](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6562)

## Implements

- [`IHistorySyncMessageAccessStatus`](../interfaces/IHistorySyncMessageAccessStatus.md)

## Constructors

### new HistorySyncMessageAccessStatus()

> **new HistorySyncMessageAccessStatus**(`p`?): [`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

Defined in: [WAProto/index.d.ts:6563](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6563)

#### Parameters

##### p?

[`IHistorySyncMessageAccessStatus`](../interfaces/IHistorySyncMessageAccessStatus.md)

#### Returns

[`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

## Properties

### completeAccessGranted?

> `optional` **completeAccessGranted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:6564](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6564)

#### Implementation of

[`IHistorySyncMessageAccessStatus`](../interfaces/IHistorySyncMessageAccessStatus.md).[`completeAccessGranted`](../interfaces/IHistorySyncMessageAccessStatus.md#completeaccessgranted)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6570](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6570)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

Defined in: [WAProto/index.d.ts:6565](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6565)

#### Parameters

##### properties?

[`IHistorySyncMessageAccessStatus`](../interfaces/IHistorySyncMessageAccessStatus.md)

#### Returns

[`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

Defined in: [WAProto/index.d.ts:6567](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6567)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6566](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6566)

#### Parameters

##### m

[`IHistorySyncMessageAccessStatus`](../interfaces/IHistorySyncMessageAccessStatus.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

Defined in: [WAProto/index.d.ts:6568](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6568)

#### Parameters

##### d

#### Returns

[`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6571](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6571)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6569](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6569)

#### Parameters

##### m

[`HistorySyncMessageAccessStatus`](HistorySyncMessageAccessStatus.md)

##### o?

`IConversionOptions`

#### Returns

`object`
