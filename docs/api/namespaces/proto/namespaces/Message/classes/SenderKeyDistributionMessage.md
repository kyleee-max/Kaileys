# Class: SenderKeyDistributionMessage

Defined in: [WAProto/index.d.ts:8871](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8871)

## Implements

- [`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

## Constructors

### new SenderKeyDistributionMessage()

> **new SenderKeyDistributionMessage**(`p`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:8872](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8872)

#### Parameters

##### p?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

## Properties

### axolotlSenderKeyDistributionMessage?

> `optional` **axolotlSenderKeyDistributionMessage**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8874](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8874)

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`axolotlSenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md#axolotlsenderkeydistributionmessage)

***

### groupId?

> `optional` **groupId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8873](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8873)

#### Implementation of

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md).[`groupId`](../interfaces/ISenderKeyDistributionMessage.md#groupid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8880](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8880)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:8875](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8875)

#### Parameters

##### properties?

[`ISenderKeyDistributionMessage`](../interfaces/ISenderKeyDistributionMessage.md)

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

Defined in: [WAProto/index.d.ts:8877](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8877)

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

Defined in: [WAProto/index.d.ts:8876](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8876)

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

Defined in: [WAProto/index.d.ts:8878](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8878)

#### Parameters

##### d

#### Returns

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8881](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8881)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8879)

#### Parameters

##### m

[`SenderKeyDistributionMessage`](SenderKeyDistributionMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
