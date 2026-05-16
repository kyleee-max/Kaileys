# Class: CallLogAction

Defined in: [WAProto/index.d.ts:11752](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11752)

## Implements

- [`ICallLogAction`](../interfaces/ICallLogAction.md)

## Constructors

### new CallLogAction()

> **new CallLogAction**(`p`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:11753](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11753)

#### Parameters

##### p?

[`ICallLogAction`](../interfaces/ICallLogAction.md)

#### Returns

[`CallLogAction`](CallLogAction.md)

## Properties

### callLogRecord?

> `optional` **callLogRecord**: `null` \| [`ICallLogRecord`](../../../interfaces/ICallLogRecord.md)

Defined in: [WAProto/index.d.ts:11754](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11754)

#### Implementation of

[`ICallLogAction`](../interfaces/ICallLogAction.md).[`callLogRecord`](../interfaces/ICallLogAction.md#calllogrecord)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11760](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11760)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:11755](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11755)

#### Parameters

##### properties?

[`ICallLogAction`](../interfaces/ICallLogAction.md)

#### Returns

[`CallLogAction`](CallLogAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:11757](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11757)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`CallLogAction`](CallLogAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11756](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11756)

#### Parameters

##### m

[`ICallLogAction`](../interfaces/ICallLogAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`CallLogAction`](CallLogAction.md)

Defined in: [WAProto/index.d.ts:11758](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11758)

#### Parameters

##### d

#### Returns

[`CallLogAction`](CallLogAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11761](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11761)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11759](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11759)

#### Parameters

##### m

[`CallLogAction`](CallLogAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
