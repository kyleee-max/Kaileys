# Class: LiveLocationMessage

Defined in: [WAProto/index.d.ts:7344](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7344)

## Implements

- [`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

## Constructors

### new LiveLocationMessage()

> **new LiveLocationMessage**(`p`?): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:7345](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7345)

#### Parameters

##### p?

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

## Properties

### accuracyInMeters?

> `optional` **accuracyInMeters**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7348](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7348)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`accuracyInMeters`](../interfaces/ILiveLocationMessage.md#accuracyinmeters)

***

### caption?

> `optional` **caption**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7351](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7351)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`caption`](../interfaces/ILiveLocationMessage.md#caption)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7355](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7355)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`contextInfo`](../interfaces/ILiveLocationMessage.md#contextinfo)

***

### degreesClockwiseFromMagneticNorth?

> `optional` **degreesClockwiseFromMagneticNorth**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7350](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7350)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`degreesClockwiseFromMagneticNorth`](../interfaces/ILiveLocationMessage.md#degreesclockwisefrommagneticnorth)

***

### degreesLatitude?

> `optional` **degreesLatitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7346](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7346)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`degreesLatitude`](../interfaces/ILiveLocationMessage.md#degreeslatitude)

***

### degreesLongitude?

> `optional` **degreesLongitude**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7347](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7347)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`degreesLongitude`](../interfaces/ILiveLocationMessage.md#degreeslongitude)

***

### jpegThumbnail?

> `optional` **jpegThumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7354](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7354)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`jpegThumbnail`](../interfaces/ILiveLocationMessage.md#jpegthumbnail)

***

### sequenceNumber?

> `optional` **sequenceNumber**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7352](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7352)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`sequenceNumber`](../interfaces/ILiveLocationMessage.md#sequencenumber)

***

### speedInMps?

> `optional` **speedInMps**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7349](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7349)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`speedInMps`](../interfaces/ILiveLocationMessage.md#speedinmps)

***

### timeOffset?

> `optional` **timeOffset**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7353](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7353)

#### Implementation of

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md).[`timeOffset`](../interfaces/ILiveLocationMessage.md#timeoffset)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7361](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7361)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:7356](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7356)

#### Parameters

##### properties?

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:7358](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7358)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7357](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7357)

#### Parameters

##### m

[`ILiveLocationMessage`](../interfaces/ILiveLocationMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LiveLocationMessage`](LiveLocationMessage.md)

Defined in: [WAProto/index.d.ts:7359](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7359)

#### Parameters

##### d

#### Returns

[`LiveLocationMessage`](LiveLocationMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7362](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7362)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7360](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7360)

#### Parameters

##### m

[`LiveLocationMessage`](LiveLocationMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
