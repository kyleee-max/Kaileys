# Class: Account

Defined in: [WAProto/index.d.ts:736](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L736)

## Implements

- [`IAccount`](../interfaces/IAccount.md)

## Constructors

### new Account()

> **new Account**(`p`?): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:737](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L737)

#### Parameters

##### p?

[`IAccount`](../interfaces/IAccount.md)

#### Returns

[`Account`](Account.md)

## Properties

### countryCode?

> `optional` **countryCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L740)

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`countryCode`](../interfaces/IAccount.md#countrycode)

***

### isUsernameDeleted?

> `optional` **isUsernameDeleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L741)

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`isUsernameDeleted`](../interfaces/IAccount.md#isusernamedeleted)

***

### lid?

> `optional` **lid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:738](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L738)

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`lid`](../interfaces/IAccount.md#lid)

***

### username?

> `optional` **username**: `null` \| `string`

Defined in: [WAProto/index.d.ts:739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L739)

#### Implementation of

[`IAccount`](../interfaces/IAccount.md).[`username`](../interfaces/IAccount.md#username)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L747)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L742)

#### Parameters

##### properties?

[`IAccount`](../interfaces/IAccount.md)

#### Returns

[`Account`](Account.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L744)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Account`](Account.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L743)

#### Parameters

##### m

[`IAccount`](../interfaces/IAccount.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Account`](Account.md)

Defined in: [WAProto/index.d.ts:745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L745)

#### Parameters

##### d

#### Returns

[`Account`](Account.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:748](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L748)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L746)

#### Parameters

##### m

[`Account`](Account.md)

##### o?

`IConversionOptions`

#### Returns

`object`
