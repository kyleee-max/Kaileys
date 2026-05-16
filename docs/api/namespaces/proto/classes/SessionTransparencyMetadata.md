# Class: SessionTransparencyMetadata

Defined in: [WAProto/index.d.ts:11036](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11036)

## Implements

- [`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md)

## Constructors

### new SessionTransparencyMetadata()

> **new SessionTransparencyMetadata**(`p`?): [`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

Defined in: [WAProto/index.d.ts:11037](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11037)

#### Parameters

##### p?

[`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md)

#### Returns

[`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

## Properties

### disclaimerText?

> `optional` **disclaimerText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11038)

#### Implementation of

[`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md).[`disclaimerText`](../interfaces/ISessionTransparencyMetadata.md#disclaimertext)

***

### hcaId?

> `optional` **hcaId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11039)

#### Implementation of

[`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md).[`hcaId`](../interfaces/ISessionTransparencyMetadata.md#hcaid)

***

### sessionTransparencyType?

> `optional` **sessionTransparencyType**: `null` \| [`SessionTransparencyType`](../enumerations/SessionTransparencyType.md)

Defined in: [WAProto/index.d.ts:11040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11040)

#### Implementation of

[`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md).[`sessionTransparencyType`](../interfaces/ISessionTransparencyMetadata.md#sessiontransparencytype)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11046](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11046)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

Defined in: [WAProto/index.d.ts:11041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11041)

#### Parameters

##### properties?

[`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md)

#### Returns

[`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

Defined in: [WAProto/index.d.ts:11043](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11043)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11042)

#### Parameters

##### m

[`ISessionTransparencyMetadata`](../interfaces/ISessionTransparencyMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

Defined in: [WAProto/index.d.ts:11044](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11044)

#### Parameters

##### d

#### Returns

[`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11047](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11047)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11045](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11045)

#### Parameters

##### m

[`SessionTransparencyMetadata`](SessionTransparencyMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
