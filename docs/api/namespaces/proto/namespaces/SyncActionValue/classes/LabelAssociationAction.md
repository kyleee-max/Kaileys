# Class: LabelAssociationAction

Defined in: [WAProto/index.d.ts:12072](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12072)

## Implements

- [`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

## Constructors

### new LabelAssociationAction()

> **new LabelAssociationAction**(`p`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:12073](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12073)

#### Parameters

##### p?

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

## Properties

### labeled?

> `optional` **labeled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12074](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12074)

#### Implementation of

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md).[`labeled`](../interfaces/ILabelAssociationAction.md#labeled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12080](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12080)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:12075](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12075)

#### Parameters

##### properties?

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:12077](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12077)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12076](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12076)

#### Parameters

##### m

[`ILabelAssociationAction`](../interfaces/ILabelAssociationAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LabelAssociationAction`](LabelAssociationAction.md)

Defined in: [WAProto/index.d.ts:12078](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12078)

#### Parameters

##### d

#### Returns

[`LabelAssociationAction`](LabelAssociationAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12081](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12081)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12079](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12079)

#### Parameters

##### m

[`LabelAssociationAction`](LabelAssociationAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
