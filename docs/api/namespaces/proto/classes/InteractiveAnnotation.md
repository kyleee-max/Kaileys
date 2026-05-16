# Class: InteractiveAnnotation

Defined in: [WAProto/index.d.ts:4832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4832)

## Implements

- [`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

## Constructors

### new InteractiveAnnotation()

> **new InteractiveAnnotation**(`p`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:4833](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4833)

#### Parameters

##### p?

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

## Properties

### action?

> `optional` **action**: `"location"` \| `"newsletter"` \| `"embeddedAction"` \| `"tapAction"`

Defined in: [WAProto/index.d.ts:4842](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4842)

***

### embeddedAction?

> `optional` **embeddedAction**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4840](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4840)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`embeddedAction`](../interfaces/IInteractiveAnnotation.md#embeddedaction)

***

### embeddedContent?

> `optional` **embeddedContent**: `null` \| [`IEmbeddedContent`](../interfaces/IEmbeddedContent.md)

Defined in: [WAProto/index.d.ts:4836](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4836)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`embeddedContent`](../interfaces/IInteractiveAnnotation.md#embeddedcontent)

***

### location?

> `optional` **location**: `null` \| [`ILocation`](../interfaces/ILocation.md)

Defined in: [WAProto/index.d.ts:4838](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4838)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`location`](../interfaces/IInteractiveAnnotation.md#location)

***

### newsletter?

> `optional` **newsletter**: `null` \| [`IForwardedNewsletterMessageInfo`](../namespaces/ContextInfo/interfaces/IForwardedNewsletterMessageInfo.md)

Defined in: [WAProto/index.d.ts:4839](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4839)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`newsletter`](../interfaces/IInteractiveAnnotation.md#newsletter)

***

### polygonVertices

> **polygonVertices**: [`IPoint`](../interfaces/IPoint.md)[]

Defined in: [WAProto/index.d.ts:4834](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4834)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`polygonVertices`](../interfaces/IInteractiveAnnotation.md#polygonvertices)

***

### shouldSkipConfirmation?

> `optional` **shouldSkipConfirmation**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4835](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4835)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`shouldSkipConfirmation`](../interfaces/IInteractiveAnnotation.md#shouldskipconfirmation)

***

### statusLinkType?

> `optional` **statusLinkType**: `null` \| [`StatusLinkType`](../namespaces/InteractiveAnnotation/enumerations/StatusLinkType.md)

Defined in: [WAProto/index.d.ts:4837](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4837)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`statusLinkType`](../interfaces/IInteractiveAnnotation.md#statuslinktype)

***

### tapAction?

> `optional` **tapAction**: `null` \| [`ITapLinkAction`](../interfaces/ITapLinkAction.md)

Defined in: [WAProto/index.d.ts:4841](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4841)

#### Implementation of

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md).[`tapAction`](../interfaces/IInteractiveAnnotation.md#tapaction)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4848](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4848)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:4843](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4843)

#### Parameters

##### properties?

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:4845](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4845)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4844](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4844)

#### Parameters

##### m

[`IInteractiveAnnotation`](../interfaces/IInteractiveAnnotation.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InteractiveAnnotation`](InteractiveAnnotation.md)

Defined in: [WAProto/index.d.ts:4846](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4846)

#### Parameters

##### d

#### Returns

[`InteractiveAnnotation`](InteractiveAnnotation.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4849](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4849)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4847](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4847)

#### Parameters

##### m

[`InteractiveAnnotation`](InteractiveAnnotation.md)

##### o?

`IConversionOptions`

#### Returns

`object`
