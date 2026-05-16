# Class: WebdPayload

Defined in: [WAProto/index.d.ts:3024](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3024)

## Implements

- [`IWebdPayload`](../interfaces/IWebdPayload.md)

## Constructors

### new WebdPayload()

> **new WebdPayload**(`p`?): [`WebdPayload`](WebdPayload.md)

Defined in: [WAProto/index.d.ts:3025](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3025)

#### Parameters

##### p?

[`IWebdPayload`](../interfaces/IWebdPayload.md)

#### Returns

[`WebdPayload`](WebdPayload.md)

## Properties

### documentTypes?

> `optional` **documentTypes**: `null` \| `string`

Defined in: [WAProto/index.d.ts:3035](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3035)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`documentTypes`](../interfaces/IWebdPayload.md#documenttypes)

***

### features?

> `optional` **features**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:3036](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3036)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`features`](../interfaces/IWebdPayload.md#features)

***

### supportsDocumentMessages?

> `optional` **supportsDocumentMessages**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3028](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3028)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsDocumentMessages`](../interfaces/IWebdPayload.md#supportsdocumentmessages)

***

### supportsE2EAudio?

> `optional` **supportsE2EAudio**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3033](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3033)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsE2EAudio`](../interfaces/IWebdPayload.md#supportse2eaudio)

***

### supportsE2EDocument?

> `optional` **supportsE2EDocument**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3034](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3034)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsE2EDocument`](../interfaces/IWebdPayload.md#supportse2edocument)

***

### supportsE2EImage?

> `optional` **supportsE2EImage**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3031](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3031)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsE2EImage`](../interfaces/IWebdPayload.md#supportse2eimage)

***

### supportsE2EVideo?

> `optional` **supportsE2EVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3032](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3032)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsE2EVideo`](../interfaces/IWebdPayload.md#supportse2evideo)

***

### supportsMediaRetry?

> `optional` **supportsMediaRetry**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3030](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3030)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsMediaRetry`](../interfaces/IWebdPayload.md#supportsmediaretry)

***

### supportsStarredMessages?

> `optional` **supportsStarredMessages**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3027](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3027)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsStarredMessages`](../interfaces/IWebdPayload.md#supportsstarredmessages)

***

### supportsUrlMessages?

> `optional` **supportsUrlMessages**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3029](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3029)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`supportsUrlMessages`](../interfaces/IWebdPayload.md#supportsurlmessages)

***

### usesParticipantInKey?

> `optional` **usesParticipantInKey**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:3026](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3026)

#### Implementation of

[`IWebdPayload`](../interfaces/IWebdPayload.md).[`usesParticipantInKey`](../interfaces/IWebdPayload.md#usesparticipantinkey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3042)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`WebdPayload`](WebdPayload.md)

Defined in: [WAProto/index.d.ts:3037](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3037)

#### Parameters

##### properties?

[`IWebdPayload`](../interfaces/IWebdPayload.md)

#### Returns

[`WebdPayload`](WebdPayload.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`WebdPayload`](WebdPayload.md)

Defined in: [WAProto/index.d.ts:3039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3039)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`WebdPayload`](WebdPayload.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3038)

#### Parameters

##### m

[`IWebdPayload`](../interfaces/IWebdPayload.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`WebdPayload`](WebdPayload.md)

Defined in: [WAProto/index.d.ts:3040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3040)

#### Parameters

##### d

#### Returns

[`WebdPayload`](WebdPayload.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3043](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3043)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3041)

#### Parameters

##### m

[`WebdPayload`](WebdPayload.md)

##### o?

`IConversionOptions`

#### Returns

`object`
