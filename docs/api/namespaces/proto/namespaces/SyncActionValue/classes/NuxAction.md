# Class: NuxAction

Defined in: [WAProto/index.d.ts:12440](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12440)

## Implements

- [`INuxAction`](../interfaces/INuxAction.md)

## Constructors

### new NuxAction()

> **new NuxAction**(`p`?): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:12441](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12441)

#### Parameters

##### p?

[`INuxAction`](../interfaces/INuxAction.md)

#### Returns

[`NuxAction`](NuxAction.md)

## Properties

### acknowledged?

> `optional` **acknowledged**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12442](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12442)

#### Implementation of

[`INuxAction`](../interfaces/INuxAction.md).[`acknowledged`](../interfaces/INuxAction.md#acknowledged)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12448](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12448)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:12443](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12443)

#### Parameters

##### properties?

[`INuxAction`](../interfaces/INuxAction.md)

#### Returns

[`NuxAction`](NuxAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:12445](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12445)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`NuxAction`](NuxAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12444](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12444)

#### Parameters

##### m

[`INuxAction`](../interfaces/INuxAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`NuxAction`](NuxAction.md)

Defined in: [WAProto/index.d.ts:12446](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12446)

#### Parameters

##### d

#### Returns

[`NuxAction`](NuxAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12449](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12449)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12447](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12447)

#### Parameters

##### m

[`NuxAction`](NuxAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
