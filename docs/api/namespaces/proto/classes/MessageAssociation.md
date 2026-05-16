# Class: MessageAssociation

Defined in: [WAProto/index.d.ts:9473](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9473)

## Implements

- [`IMessageAssociation`](../interfaces/IMessageAssociation.md)

## Constructors

### new MessageAssociation()

> **new MessageAssociation**(`p`?): [`MessageAssociation`](MessageAssociation.md)

Defined in: [WAProto/index.d.ts:9474](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9474)

#### Parameters

##### p?

[`IMessageAssociation`](../interfaces/IMessageAssociation.md)

#### Returns

[`MessageAssociation`](MessageAssociation.md)

## Properties

### associationType?

> `optional` **associationType**: `null` \| [`AssociationType`](../namespaces/MessageAssociation/enumerations/AssociationType.md)

Defined in: [WAProto/index.d.ts:9475](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9475)

#### Implementation of

[`IMessageAssociation`](../interfaces/IMessageAssociation.md).[`associationType`](../interfaces/IMessageAssociation.md#associationtype)

***

### messageIndex?

> `optional` **messageIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:9477](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9477)

#### Implementation of

[`IMessageAssociation`](../interfaces/IMessageAssociation.md).[`messageIndex`](../interfaces/IMessageAssociation.md#messageindex)

***

### parentMessageKey?

> `optional` **parentMessageKey**: `null` \| [`IMessageKey`](../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:9476](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9476)

#### Implementation of

[`IMessageAssociation`](../interfaces/IMessageAssociation.md).[`parentMessageKey`](../interfaces/IMessageAssociation.md#parentmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:9483](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9483)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MessageAssociation`](MessageAssociation.md)

Defined in: [WAProto/index.d.ts:9478](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9478)

#### Parameters

##### properties?

[`IMessageAssociation`](../interfaces/IMessageAssociation.md)

#### Returns

[`MessageAssociation`](MessageAssociation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MessageAssociation`](MessageAssociation.md)

Defined in: [WAProto/index.d.ts:9480](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9480)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MessageAssociation`](MessageAssociation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:9479](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9479)

#### Parameters

##### m

[`IMessageAssociation`](../interfaces/IMessageAssociation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MessageAssociation`](MessageAssociation.md)

Defined in: [WAProto/index.d.ts:9481](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9481)

#### Parameters

##### d

#### Returns

[`MessageAssociation`](MessageAssociation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:9484](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9484)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:9482](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L9482)

#### Parameters

##### m

[`MessageAssociation`](MessageAssociation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
