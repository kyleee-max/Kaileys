# Class: SecretEncryptedMessage

Defined in: [WAProto/index.d.ts:8820](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8820)

## Implements

- [`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

## Constructors

### new SecretEncryptedMessage()

> **new SecretEncryptedMessage**(`p`?): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:8821](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8821)

#### Parameters

##### p?

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

## Properties

### encIv?

> `optional` **encIv**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8824)

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`encIv`](../interfaces/ISecretEncryptedMessage.md#enciv)

***

### encPayload?

> `optional` **encPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8823](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8823)

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`encPayload`](../interfaces/ISecretEncryptedMessage.md#encpayload)

***

### secretEncType?

> `optional` **secretEncType**: `null` \| [`SecretEncType`](../namespaces/SecretEncryptedMessage/enumerations/SecretEncType.md)

Defined in: [WAProto/index.d.ts:8825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8825)

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`secretEncType`](../interfaces/ISecretEncryptedMessage.md#secretenctype)

***

### targetMessageKey?

> `optional` **targetMessageKey**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8822](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8822)

#### Implementation of

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md).[`targetMessageKey`](../interfaces/ISecretEncryptedMessage.md#targetmessagekey)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8831](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8831)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:8826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8826)

#### Parameters

##### properties?

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:8828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8828)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8827)

#### Parameters

##### m

[`ISecretEncryptedMessage`](../interfaces/ISecretEncryptedMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SecretEncryptedMessage`](SecretEncryptedMessage.md)

Defined in: [WAProto/index.d.ts:8829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8829)

#### Parameters

##### d

#### Returns

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8832](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8832)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8830)

#### Parameters

##### m

[`SecretEncryptedMessage`](SecretEncryptedMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
