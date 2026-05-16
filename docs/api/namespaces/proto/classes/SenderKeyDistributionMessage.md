# Class: SenderKeyDistributionMessage

Defined in: [WAProto/index.d.ts:10728](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10728)

## Implements

- [`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

## Constructors

### new SenderKeyDistributionMessage()

> **new SenderKeyDistributionMessage**(`p`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:10729](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10729)

#### Parameters

##### p?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

## Properties

### chainKey?

> `optional` **chainKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10732](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10732)

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`chainKey`](../interfaces/ISenderKeyDistributionMessage.md#chainkey)

***

### id?

> `optional` **id**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10730](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10730)

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`id`](../interfaces/ISenderKeyDistributionMessage.md#id)

***

### iteration?

> `optional` **iteration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10731](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10731)

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`iteration`](../interfaces/ISenderKeyDistributionMessage.md#iteration)

***

### signingKey?

> `optional` **signingKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10733](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10733)

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`signingKey`](../interfaces/ISenderKeyDistributionMessage.md#signingkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10739)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:10734](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10734)

#### Parameters

##### properties?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:10736](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10736)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10735](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10735)

#### Parameters

##### m

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:10737](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10737)

#### Parameters

##### d

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10740)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10738](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10738)

#### Parameters

##### m

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
