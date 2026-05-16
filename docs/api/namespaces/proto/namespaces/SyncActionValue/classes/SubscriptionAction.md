# Class: SubscriptionAction

Defined in: [WAProto/index.d.ts:12808](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12808)

## Implements

- [`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

## Constructors

### new SubscriptionAction()

> **new SubscriptionAction**(`p`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:12809](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12809)

#### Parameters

##### p?

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

## Properties

### expirationDate?

> `optional` **expirationDate**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12812](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12812)

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`expirationDate`](../interfaces/ISubscriptionAction.md#expirationdate)

***

### isAutoRenewing?

> `optional` **isAutoRenewing**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12811](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12811)

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`isAutoRenewing`](../interfaces/ISubscriptionAction.md#isautorenewing)

***

### isDeactivated?

> `optional` **isDeactivated**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12810](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12810)

#### Implementation of

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md).[`isDeactivated`](../interfaces/ISubscriptionAction.md#isdeactivated)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12818](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12818)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:12813](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12813)

#### Parameters

##### properties?

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:12815](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12815)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12814](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12814)

#### Parameters

##### m

[`ISubscriptionAction`](../interfaces/ISubscriptionAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SubscriptionAction`](SubscriptionAction.md)

Defined in: [WAProto/index.d.ts:12816](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12816)

#### Parameters

##### d

#### Returns

[`SubscriptionAction`](SubscriptionAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12819](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12819)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12817](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12817)

#### Parameters

##### m

[`SubscriptionAction`](SubscriptionAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
