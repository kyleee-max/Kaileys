# Class: HydratedURLButton

Defined in: [WAProto/index.d.ts:4669](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4669)

## Implements

- [`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

## Constructors

### new HydratedURLButton()

> **new HydratedURLButton**(`p`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:4670](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4670)

#### Parameters

##### p?

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

## Properties

### consentedUsersUrl?

> `optional` **consentedUsersUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4673](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4673)

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`consentedUsersUrl`](../interfaces/IHydratedURLButton.md#consentedusersurl)

***

### displayText?

> `optional` **displayText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4671](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4671)

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`displayText`](../interfaces/IHydratedURLButton.md#displaytext)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4672](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4672)

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`url`](../interfaces/IHydratedURLButton.md#url)

***

### webviewPresentation?

> `optional` **webviewPresentation**: `null` \| [`WebviewPresentationType`](../namespaces/HydratedURLButton/enumerations/WebviewPresentationType.md)

Defined in: [WAProto/index.d.ts:4674](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4674)

#### Implementation of

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md).[`webviewPresentation`](../interfaces/IHydratedURLButton.md#webviewpresentation)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4680](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4680)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:4675](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4675)

#### Parameters

##### properties?

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:4677](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4677)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4676](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4676)

#### Parameters

##### m

[`IHydratedURLButton`](../interfaces/IHydratedURLButton.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`HydratedURLButton`](HydratedURLButton.md)

Defined in: [WAProto/index.d.ts:4678](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4678)

#### Parameters

##### d

#### Returns

[`HydratedURLButton`](HydratedURLButton.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4681](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4681)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4679](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4679)

#### Parameters

##### m

[`HydratedURLButton`](HydratedURLButton.md)

##### o?

`IConversionOptions`

#### Returns

`object`
