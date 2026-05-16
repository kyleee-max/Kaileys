# Class: ScheduledCallEditMessage

Defined in: [WAProto/index.d.ts:8792](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8792)

## Implements

- [`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

## Constructors

### new ScheduledCallEditMessage()

> **new ScheduledCallEditMessage**(`p`?): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:8793](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8793)

#### Parameters

##### p?

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

## Properties

### editType?

> `optional` **editType**: `null` \| [`EditType`](../namespaces/ScheduledCallEditMessage/enumerations/EditType.md)

Defined in: [WAProto/index.d.ts:8795](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8795)

#### Implementation of

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md).[`editType`](../interfaces/IScheduledCallEditMessage.md#edittype)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8794](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8794)

#### Implementation of

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md).[`key`](../interfaces/IScheduledCallEditMessage.md#key)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8801](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8801)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:8796](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8796)

#### Parameters

##### properties?

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:8798](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8798)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8797](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8797)

#### Parameters

##### m

[`IScheduledCallEditMessage`](../interfaces/IScheduledCallEditMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

Defined in: [WAProto/index.d.ts:8799](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8799)

#### Parameters

##### d

#### Returns

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8802](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8802)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8800](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8800)

#### Parameters

##### m

[`ScheduledCallEditMessage`](ScheduledCallEditMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
