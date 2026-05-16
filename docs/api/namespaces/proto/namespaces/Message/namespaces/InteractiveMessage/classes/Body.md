# Class: Body

Defined in: [WAProto/index.d.ts:6771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6771)

## Implements

- [`IBody`](../interfaces/IBody.md)

## Constructors

### new Body()

> **new Body**(`p`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6772)

#### Parameters

##### p?

[`IBody`](../interfaces/IBody.md)

#### Returns

[`Body`](Body.md)

## Properties

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:6773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6773)

#### Implementation of

[`IBody`](../interfaces/IBody.md).[`text`](../interfaces/IBody.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6779](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6779)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6774)

#### Parameters

##### properties?

[`IBody`](../interfaces/IBody.md)

#### Returns

[`Body`](Body.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6776)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Body`](Body.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6775)

#### Parameters

##### m

[`IBody`](../interfaces/IBody.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Body`](Body.md)

Defined in: [WAProto/index.d.ts:6777](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6777)

#### Parameters

##### d

#### Returns

[`Body`](Body.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6780](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6780)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6778](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6778)

#### Parameters

##### m

[`Body`](Body.md)

##### o?

`IConversionOptions`

#### Returns

`object`
