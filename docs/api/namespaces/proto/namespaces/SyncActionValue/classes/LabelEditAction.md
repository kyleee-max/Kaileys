# Class: LabelEditAction

Defined in: [WAProto/index.d.ts:12096](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12096)

## Implements

- [`ILabelEditAction`](../interfaces/ILabelEditAction.md)

## Constructors

### new LabelEditAction()

> **new LabelEditAction**(`p`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:12097](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12097)

#### Parameters

##### p?

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

#### Returns

[`LabelEditAction`](LabelEditAction.md)

## Properties

### color?

> `optional` **color**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12099](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12099)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`color`](../interfaces/ILabelEditAction.md#color)

***

### deleted?

> `optional` **deleted**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12101](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12101)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`deleted`](../interfaces/ILabelEditAction.md#deleted)

***

### isActive?

> `optional` **isActive**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12103](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12103)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`isActive`](../interfaces/ILabelEditAction.md#isactive)

***

### isImmutable?

> `optional` **isImmutable**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:12105](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12105)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`isImmutable`](../interfaces/ILabelEditAction.md#isimmutable)

***

### muteEndTimeMs?

> `optional` **muteEndTimeMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:12106](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12106)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`muteEndTimeMs`](../interfaces/ILabelEditAction.md#muteendtimems)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12098](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12098)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`name`](../interfaces/ILabelEditAction.md#name)

***

### orderIndex?

> `optional` **orderIndex**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12102](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12102)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`orderIndex`](../interfaces/ILabelEditAction.md#orderindex)

***

### predefinedId?

> `optional` **predefinedId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:12100](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12100)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`predefinedId`](../interfaces/ILabelEditAction.md#predefinedid)

***

### type?

> `optional` **type**: `null` \| [`ListType`](../namespaces/LabelEditAction/enumerations/ListType.md)

Defined in: [WAProto/index.d.ts:12104](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12104)

#### Implementation of

[`ILabelEditAction`](../interfaces/ILabelEditAction.md).[`type`](../interfaces/ILabelEditAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12112](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12112)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:12107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12107)

#### Parameters

##### properties?

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

#### Returns

[`LabelEditAction`](LabelEditAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:12109](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12109)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LabelEditAction`](LabelEditAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12108](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12108)

#### Parameters

##### m

[`ILabelEditAction`](../interfaces/ILabelEditAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LabelEditAction`](LabelEditAction.md)

Defined in: [WAProto/index.d.ts:12110](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12110)

#### Parameters

##### d

#### Returns

[`LabelEditAction`](LabelEditAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12113](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12113)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12111](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12111)

#### Parameters

##### m

[`LabelEditAction`](LabelEditAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
