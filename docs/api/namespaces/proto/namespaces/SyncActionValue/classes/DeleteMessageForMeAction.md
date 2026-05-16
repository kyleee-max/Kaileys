# Class: DeleteMessageForMeAction

Defined in: [WAProto/index.d.ts:11949](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11949)

## Implements

- [`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

## Constructors

### new DeleteMessageForMeAction()

> **new DeleteMessageForMeAction**(`p`?): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:11950](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11950)

#### Parameters

##### p?

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

## Properties

### deleteMedia?

> `optional` **deleteMedia**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11951](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11951)

#### Implementation of

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md).[`deleteMedia`](../interfaces/IDeleteMessageForMeAction.md#deletemedia)

***

### messageTimestamp?

> `optional` **messageTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:11952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11952)

#### Implementation of

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md).[`messageTimestamp`](../interfaces/IDeleteMessageForMeAction.md#messagetimestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11958](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11958)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:11953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11953)

#### Parameters

##### properties?

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:11955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11955)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11954)

#### Parameters

##### m

[`IDeleteMessageForMeAction`](../interfaces/IDeleteMessageForMeAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

Defined in: [WAProto/index.d.ts:11956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11956)

#### Parameters

##### d

#### Returns

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11959](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11959)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11957](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11957)

#### Parameters

##### m

[`DeleteMessageForMeAction`](DeleteMessageForMeAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
