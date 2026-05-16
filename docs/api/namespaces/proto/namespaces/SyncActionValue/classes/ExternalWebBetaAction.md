# Class: ExternalWebBetaAction

Defined in: [WAProto/index.d.ts:11982](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11982)

## Implements

- [`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

## Constructors

### new ExternalWebBetaAction()

> **new ExternalWebBetaAction**(`p`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:11983](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11983)

#### Parameters

##### p?

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

## Properties

### isOptIn?

> `optional` **isOptIn**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11984](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11984)

#### Implementation of

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md).[`isOptIn`](../interfaces/IExternalWebBetaAction.md#isoptin)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11990](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11990)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:11985](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11985)

#### Parameters

##### properties?

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:11987](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11987)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11986](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11986)

#### Parameters

##### m

[`IExternalWebBetaAction`](../interfaces/IExternalWebBetaAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ExternalWebBetaAction`](ExternalWebBetaAction.md)

Defined in: [WAProto/index.d.ts:11988](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11988)

#### Parameters

##### d

#### Returns

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11991)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11989](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11989)

#### Parameters

##### m

[`ExternalWebBetaAction`](ExternalWebBetaAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
