# Class: AutoDownloadSettings

Defined in: [WAProto/index.d.ts:776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L776)

## Implements

- [`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

## Constructors

### new AutoDownloadSettings()

> **new AutoDownloadSettings**(`p`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:777](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L777)

#### Parameters

##### p?

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

## Properties

### downloadAudio?

> `optional` **downloadAudio**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:779](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L779)

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadAudio`](../interfaces/IAutoDownloadSettings.md#downloadaudio)

***

### downloadDocuments?

> `optional` **downloadDocuments**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:781](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L781)

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadDocuments`](../interfaces/IAutoDownloadSettings.md#downloaddocuments)

***

### downloadImages?

> `optional` **downloadImages**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:778](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L778)

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadImages`](../interfaces/IAutoDownloadSettings.md#downloadimages)

***

### downloadVideo?

> `optional` **downloadVideo**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:780](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L780)

#### Implementation of

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md).[`downloadVideo`](../interfaces/IAutoDownloadSettings.md#downloadvideo)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:787](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L787)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:782](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L782)

#### Parameters

##### properties?

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:784](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L784)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:783](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L783)

#### Parameters

##### m

[`IAutoDownloadSettings`](../interfaces/IAutoDownloadSettings.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AutoDownloadSettings`](AutoDownloadSettings.md)

Defined in: [WAProto/index.d.ts:785](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L785)

#### Parameters

##### d

#### Returns

[`AutoDownloadSettings`](AutoDownloadSettings.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:788](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L788)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:786](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L786)

#### Parameters

##### m

[`AutoDownloadSettings`](AutoDownloadSettings.md)

##### o?

`IConversionOptions`

#### Returns

`object`
