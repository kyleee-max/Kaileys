# Class: BotLinkedAccountsMetadata

Defined in: [WAProto/index.d.ts:1334](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1334)

## Implements

- [`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

## Constructors

### new BotLinkedAccountsMetadata()

> **new BotLinkedAccountsMetadata**(`p`?): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:1335](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1335)

#### Parameters

##### p?

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

## Properties

### acAuthTokens?

> `optional` **acAuthTokens**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:1337](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1337)

#### Implementation of

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md).[`acAuthTokens`](../interfaces/IBotLinkedAccountsMetadata.md#acauthtokens)

***

### accounts

> **accounts**: [`IBotLinkedAccount`](../interfaces/IBotLinkedAccount.md)[]

Defined in: [WAProto/index.d.ts:1336](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1336)

#### Implementation of

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md).[`accounts`](../interfaces/IBotLinkedAccountsMetadata.md#accounts)

***

### acErrorCode?

> `optional` **acErrorCode**: `null` \| `number`

Defined in: [WAProto/index.d.ts:1338](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1338)

#### Implementation of

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md).[`acErrorCode`](../interfaces/IBotLinkedAccountsMetadata.md#acerrorcode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:1344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1344)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:1339](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1339)

#### Parameters

##### properties?

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:1341](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1341)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:1340](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1340)

#### Parameters

##### m

[`IBotLinkedAccountsMetadata`](../interfaces/IBotLinkedAccountsMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

Defined in: [WAProto/index.d.ts:1342](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1342)

#### Parameters

##### d

#### Returns

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:1345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1345)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:1343](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L1343)

#### Parameters

##### m

[`BotLinkedAccountsMetadata`](BotLinkedAccountsMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
