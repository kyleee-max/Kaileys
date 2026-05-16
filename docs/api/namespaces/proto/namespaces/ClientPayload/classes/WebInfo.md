# Class: WebInfo

Defined in: [WAProto/index.d.ts:2984](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2984)

## Implements

- [`IWebInfo`](../interfaces/IWebInfo.md)

## Constructors

### new WebInfo()

> **new WebInfo**(`p`?): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:2985](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2985)

#### Parameters

##### p?

[`IWebInfo`](../interfaces/IWebInfo.md)

#### Returns

[`WebInfo`](WebInfo.md)

## Properties

### refToken?

> `optional` **refToken**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2986](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2986)

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`refToken`](../interfaces/IWebInfo.md#reftoken)

***

### version?

> `optional` **version**: `null` \| `string`

Defined in: [WAProto/index.d.ts:2987](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2987)

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`version`](../interfaces/IWebInfo.md#version)

***

### webdPayload?

> `optional` **webdPayload**: `null` \| [`IWebdPayload`](../namespaces/WebInfo/interfaces/IWebdPayload.md)

Defined in: [WAProto/index.d.ts:2988](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2988)

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`webdPayload`](../interfaces/IWebInfo.md#webdpayload)

***

### webSubPlatform?

> `optional` **webSubPlatform**: `null` \| [`WebSubPlatform`](../namespaces/WebInfo/enumerations/WebSubPlatform.md)

Defined in: [WAProto/index.d.ts:2989](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2989)

#### Implementation of

[`IWebInfo`](../interfaces/IWebInfo.md).[`webSubPlatform`](../interfaces/IWebInfo.md#websubplatform)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2995](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2995)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:2990](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2990)

#### Parameters

##### properties?

[`IWebInfo`](../interfaces/IWebInfo.md)

#### Returns

[`WebInfo`](WebInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:2992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2992)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WebInfo`](WebInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2991](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2991)

#### Parameters

##### m

[`IWebInfo`](../interfaces/IWebInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WebInfo`](WebInfo.md)

Defined in: [WAProto/index.d.ts:2993](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2993)

#### Parameters

##### d

#### Returns

[`WebInfo`](WebInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2996](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2996)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2994](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2994)

#### Parameters

##### m

[`WebInfo`](WebInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
