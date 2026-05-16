# Class: ProloguePayload

Defined in: [WAProto/index.d.ts:10574](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10574)

## Implements

- [`IProloguePayload`](../interfaces/IProloguePayload.md)

## Constructors

### new ProloguePayload()

> **new ProloguePayload**(`p`?): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:10575](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10575)

#### Parameters

##### p?

[`IProloguePayload`](../interfaces/IProloguePayload.md)

#### Returns

[`ProloguePayload`](ProloguePayload.md)

## Properties

### commitment?

> `optional` **commitment**: `null` \| [`ICompanionCommitment`](../interfaces/ICompanionCommitment.md)

Defined in: [WAProto/index.d.ts:10577](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10577)

#### Implementation of

[`IProloguePayload`](../interfaces/IProloguePayload.md).[`commitment`](../interfaces/IProloguePayload.md#commitment)

***

### companionEphemeralIdentity?

> `optional` **companionEphemeralIdentity**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10576](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10576)

#### Implementation of

[`IProloguePayload`](../interfaces/IProloguePayload.md).[`companionEphemeralIdentity`](../interfaces/IProloguePayload.md#companionephemeralidentity)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10583](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10583)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:10578](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10578)

#### Parameters

##### properties?

[`IProloguePayload`](../interfaces/IProloguePayload.md)

#### Returns

[`ProloguePayload`](ProloguePayload.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:10580](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10580)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProloguePayload`](ProloguePayload.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10579](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10579)

#### Parameters

##### m

[`IProloguePayload`](../interfaces/IProloguePayload.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProloguePayload`](ProloguePayload.md)

Defined in: [WAProto/index.d.ts:10581](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10581)

#### Parameters

##### d

#### Returns

[`ProloguePayload`](ProloguePayload.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10584](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10584)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10582](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10582)

#### Parameters

##### m

[`ProloguePayload`](ProloguePayload.md)

##### o?

`IConversionOptions`

#### Returns

`object`
