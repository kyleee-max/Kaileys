# Class: SignalMessage

Defined in: [WAProto/index.d.ts:11062](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11062)

## Implements

- [`ISignalMessage`](../interfaces/ISignalMessage.md)

## Constructors

### new SignalMessage()

> **new SignalMessage**(`p`?): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:11063](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11063)

#### Parameters

##### p?

[`ISignalMessage`](../interfaces/ISignalMessage.md)

#### Returns

[`SignalMessage`](SignalMessage.md)

## Properties

### ciphertext?

> `optional` **ciphertext**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11067](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11067)

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`ciphertext`](../interfaces/ISignalMessage.md#ciphertext)

***

### counter?

> `optional` **counter**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11065](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11065)

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`counter`](../interfaces/ISignalMessage.md#counter)

***

### previousCounter?

> `optional` **previousCounter**: `null` \| `number`

Defined in: [WAProto/index.d.ts:11066](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11066)

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`previousCounter`](../interfaces/ISignalMessage.md#previouscounter)

***

### ratchetKey?

> `optional` **ratchetKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:11064](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11064)

#### Implementation of

[`ISignalMessage`](../interfaces/ISignalMessage.md).[`ratchetKey`](../interfaces/ISignalMessage.md#ratchetkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11073](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11073)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:11068](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11068)

#### Parameters

##### properties?

[`ISignalMessage`](../interfaces/ISignalMessage.md)

#### Returns

[`SignalMessage`](SignalMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:11070](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11070)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SignalMessage`](SignalMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11069](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11069)

#### Parameters

##### m

[`ISignalMessage`](../interfaces/ISignalMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SignalMessage`](SignalMessage.md)

Defined in: [WAProto/index.d.ts:11071](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11071)

#### Parameters

##### d

#### Returns

[`SignalMessage`](SignalMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11074](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11074)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11072)

#### Parameters

##### m

[`SignalMessage`](SignalMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
