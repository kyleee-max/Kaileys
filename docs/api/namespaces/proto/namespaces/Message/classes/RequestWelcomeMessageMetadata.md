# Class: RequestWelcomeMessageMetadata

Defined in: [WAProto/index.d.ts:8738](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8738)

## Implements

- [`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

## Constructors

### new RequestWelcomeMessageMetadata()

> **new RequestWelcomeMessageMetadata**(`p`?): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:8739](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8739)

#### Parameters

##### p?

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

## Properties

### localChatState?

> `optional` **localChatState**: `null` \| [`LocalChatState`](../namespaces/RequestWelcomeMessageMetadata/enumerations/LocalChatState.md)

Defined in: [WAProto/index.d.ts:8740](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8740)

#### Implementation of

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md).[`localChatState`](../interfaces/IRequestWelcomeMessageMetadata.md#localchatstate)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8746](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8746)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:8741](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8741)

#### Parameters

##### properties?

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:8743](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8743)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8742](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8742)

#### Parameters

##### m

[`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:8744](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8744)

#### Parameters

##### d

#### Returns

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8747](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8747)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8745](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8745)

#### Parameters

##### m

[`RequestWelcomeMessageMetadata`](RequestWelcomeMessageMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
