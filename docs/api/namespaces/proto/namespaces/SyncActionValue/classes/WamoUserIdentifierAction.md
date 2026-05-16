# Class: WamoUserIdentifierAction

Defined in: [WAProto/index.d.ts:12977](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12977)

## Implements

- [`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

## Constructors

### new WamoUserIdentifierAction()

> **new WamoUserIdentifierAction**(`p`?): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:12978](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12978)

#### Parameters

##### p?

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

## Properties

### identifier?

> `optional` **identifier**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12979](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12979)

#### Implementation of

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md).[`identifier`](../interfaces/IWamoUserIdentifierAction.md#identifier)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12985](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12985)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:12980](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12980)

#### Parameters

##### properties?

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:12982](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12982)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12981](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12981)

#### Parameters

##### m

[`IWamoUserIdentifierAction`](../interfaces/IWamoUserIdentifierAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

Defined in: [WAProto/index.d.ts:12983](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12983)

#### Parameters

##### d

#### Returns

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12986](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12986)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12984](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12984)

#### Parameters

##### m

[`WamoUserIdentifierAction`](WamoUserIdentifierAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
