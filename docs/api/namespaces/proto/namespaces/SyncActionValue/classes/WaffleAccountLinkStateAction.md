# Class: WaffleAccountLinkStateAction

Defined in: [WAProto/index.d.ts:12952](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12952)

## Implements

- [`IWaffleAccountLinkStateAction`](../interfaces/IWaffleAccountLinkStateAction.md)

## Constructors

### new WaffleAccountLinkStateAction()

> **new WaffleAccountLinkStateAction**(`p`?): [`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

Defined in: [WAProto/index.d.ts:12953](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12953)

#### Parameters

##### p?

[`IWaffleAccountLinkStateAction`](../interfaces/IWaffleAccountLinkStateAction.md)

#### Returns

[`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

## Properties

### linkState?

> `optional` **linkState**: `null` \| [`AccountLinkState`](../namespaces/WaffleAccountLinkStateAction/enumerations/AccountLinkState.md)

Defined in: [WAProto/index.d.ts:12954](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12954)

#### Implementation of

[`IWaffleAccountLinkStateAction`](../interfaces/IWaffleAccountLinkStateAction.md).[`linkState`](../interfaces/IWaffleAccountLinkStateAction.md#linkstate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12960](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12960)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

Defined in: [WAProto/index.d.ts:12955](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12955)

#### Parameters

##### properties?

[`IWaffleAccountLinkStateAction`](../interfaces/IWaffleAccountLinkStateAction.md)

#### Returns

[`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

Defined in: [WAProto/index.d.ts:12957](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12957)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12956](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12956)

#### Parameters

##### m

[`IWaffleAccountLinkStateAction`](../interfaces/IWaffleAccountLinkStateAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

Defined in: [WAProto/index.d.ts:12958](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12958)

#### Parameters

##### d

#### Returns

[`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12961](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12961)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12959](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12959)

#### Parameters

##### m

[`WaffleAccountLinkStateAction`](WaffleAccountLinkStateAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
