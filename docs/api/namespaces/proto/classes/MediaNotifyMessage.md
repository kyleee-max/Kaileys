# Class: MediaNotifyMessage

Defined in: [WAProto/index.d.ts:5115](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5115)

## Implements

- [`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

## Constructors

### new MediaNotifyMessage()

> **new MediaNotifyMessage**(`p`?): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:5116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5116)

#### Parameters

##### p?

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

## Properties

### expressPathUrl?

> `optional` **expressPathUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5117)

#### Implementation of

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md).[`expressPathUrl`](../interfaces/IMediaNotifyMessage.md#expresspathurl)

***

### fileEncSha256?

> `optional` **fileEncSha256**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5118)

#### Implementation of

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md).[`fileEncSha256`](../interfaces/IMediaNotifyMessage.md#fileencsha256)

***

### fileLength?

> `optional` **fileLength**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5119)

#### Implementation of

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md).[`fileLength`](../interfaces/IMediaNotifyMessage.md#filelength)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5125)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:5120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5120)

#### Parameters

##### properties?

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:5122](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5122)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5121)

#### Parameters

##### m

[`IMediaNotifyMessage`](../interfaces/IMediaNotifyMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`MediaNotifyMessage`](MediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:5123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5123)

#### Parameters

##### d

#### Returns

[`MediaNotifyMessage`](MediaNotifyMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5126)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5124)

#### Parameters

##### m

[`MediaNotifyMessage`](MediaNotifyMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
