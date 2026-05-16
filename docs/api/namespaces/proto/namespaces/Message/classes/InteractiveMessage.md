# Class: InteractiveMessage

Defined in: [WAProto/index.d.ts:6744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6744)

## Implements

- [`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

## Constructors

### new InteractiveMessage()

> **new InteractiveMessage**(`p`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:6745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6745)

#### Parameters

##### p?

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

## Properties

### body?

> `optional` **body**: `null` \| [`IBody`](../namespaces/InteractiveMessage/interfaces/IBody.md)

Defined in: [WAProto/index.d.ts:6747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6747)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`body`](../interfaces/IInteractiveMessage.md#body)

***

### carouselMessage?

> `optional` **carouselMessage**: `null` \| [`ICarouselMessage`](../namespaces/InteractiveMessage/interfaces/ICarouselMessage.md)

Defined in: [WAProto/index.d.ts:6754](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6754)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`carouselMessage`](../interfaces/IInteractiveMessage.md#carouselmessage)

***

### collectionMessage?

> `optional` **collectionMessage**: `null` \| [`ICollectionMessage`](../namespaces/InteractiveMessage/interfaces/ICollectionMessage.md)

Defined in: [WAProto/index.d.ts:6752](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6752)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`collectionMessage`](../interfaces/IInteractiveMessage.md#collectionmessage)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:6749](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6749)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`contextInfo`](../interfaces/IInteractiveMessage.md#contextinfo)

***

### footer?

> `optional` **footer**: `null` \| [`IFooter`](../namespaces/InteractiveMessage/interfaces/IFooter.md)

Defined in: [WAProto/index.d.ts:6748](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6748)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`footer`](../interfaces/IInteractiveMessage.md#footer)

***

### header?

> `optional` **header**: `null` \| [`IHeader`](../namespaces/InteractiveMessage/interfaces/IHeader.md)

Defined in: [WAProto/index.d.ts:6746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6746)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`header`](../interfaces/IInteractiveMessage.md#header)

***

### interactiveMessage?

> `optional` **interactiveMessage**: `"shopStorefrontMessage"` \| `"collectionMessage"` \| `"nativeFlowMessage"` \| `"carouselMessage"`

Defined in: [WAProto/index.d.ts:6755](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6755)

***

### nativeFlowMessage?

> `optional` **nativeFlowMessage**: `null` \| [`INativeFlowMessage`](../namespaces/InteractiveMessage/interfaces/INativeFlowMessage.md)

Defined in: [WAProto/index.d.ts:6753](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6753)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`nativeFlowMessage`](../interfaces/IInteractiveMessage.md#nativeflowmessage)

***

### shopStorefrontMessage?

> `optional` **shopStorefrontMessage**: `null` \| [`IShopMessage`](../namespaces/InteractiveMessage/interfaces/IShopMessage.md)

Defined in: [WAProto/index.d.ts:6751](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6751)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`shopStorefrontMessage`](../interfaces/IInteractiveMessage.md#shopstorefrontmessage)

***

### urlTrackingMap?

> `optional` **urlTrackingMap**: `null` \| [`IUrlTrackingMap`](../../../interfaces/IUrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:6750](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6750)

#### Implementation of

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md).[`urlTrackingMap`](../interfaces/IInteractiveMessage.md#urltrackingmap)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:6761](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6761)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:6756](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6756)

#### Parameters

##### properties?

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:6758](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6758)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:6757](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6757)

#### Parameters

##### m

[`IInteractiveMessage`](../interfaces/IInteractiveMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InteractiveMessage`](InteractiveMessage.md)

Defined in: [WAProto/index.d.ts:6759](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6759)

#### Parameters

##### d

#### Returns

[`InteractiveMessage`](InteractiveMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:6762](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6762)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:6760](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L6760)

#### Parameters

##### m

[`InteractiveMessage`](InteractiveMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
