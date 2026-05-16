# Class: SessionStructure

Defined in: [WAProto/index.d.ts:10890](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10890)

## Implements

- [`ISessionStructure`](../interfaces/ISessionStructure.md)

## Constructors

### new SessionStructure()

> **new SessionStructure**(`p`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:10891](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10891)

#### Parameters

##### p?

[`ISessionStructure`](../interfaces/ISessionStructure.md)

#### Returns

[`SessionStructure`](SessionStructure.md)

## Properties

### aliceBaseKey?

> `optional` **aliceBaseKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10904)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`aliceBaseKey`](../interfaces/ISessionStructure.md#alicebasekey)

***

### localIdentityPublic?

> `optional` **localIdentityPublic**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10893](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10893)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`localIdentityPublic`](../interfaces/ISessionStructure.md#localidentitypublic)

***

### localRegistrationId?

> `optional` **localRegistrationId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10902](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10902)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`localRegistrationId`](../interfaces/ISessionStructure.md#localregistrationid)

***

### needsRefresh?

> `optional` **needsRefresh**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:10903](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10903)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`needsRefresh`](../interfaces/ISessionStructure.md#needsrefresh)

***

### pendingKeyExchange?

> `optional` **pendingKeyExchange**: `null` \| [`IPendingKeyExchange`](../namespaces/SessionStructure/interfaces/IPendingKeyExchange.md)

Defined in: [WAProto/index.d.ts:10899](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10899)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`pendingKeyExchange`](../interfaces/ISessionStructure.md#pendingkeyexchange)

***

### pendingPreKey?

> `optional` **pendingPreKey**: `null` \| [`IPendingPreKey`](../namespaces/SessionStructure/interfaces/IPendingPreKey.md)

Defined in: [WAProto/index.d.ts:10900](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10900)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`pendingPreKey`](../interfaces/ISessionStructure.md#pendingprekey)

***

### previousCounter?

> `optional` **previousCounter**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10896](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10896)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`previousCounter`](../interfaces/ISessionStructure.md#previouscounter)

***

### receiverChains

> **receiverChains**: [`IChain`](../namespaces/SessionStructure/interfaces/IChain.md)[]

Defined in: [WAProto/index.d.ts:10898](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10898)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`receiverChains`](../interfaces/ISessionStructure.md#receiverchains)

***

### remoteIdentityPublic?

> `optional` **remoteIdentityPublic**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10894](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10894)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`remoteIdentityPublic`](../interfaces/ISessionStructure.md#remoteidentitypublic)

***

### remoteRegistrationId?

> `optional` **remoteRegistrationId**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10901)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`remoteRegistrationId`](../interfaces/ISessionStructure.md#remoteregistrationid)

***

### rootKey?

> `optional` **rootKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:10895](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10895)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`rootKey`](../interfaces/ISessionStructure.md#rootkey)

***

### senderChain?

> `optional` **senderChain**: `null` \| [`IChain`](../namespaces/SessionStructure/interfaces/IChain.md)

Defined in: [WAProto/index.d.ts:10897](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10897)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`senderChain`](../interfaces/ISessionStructure.md#senderchain)

***

### sessionVersion?

> `optional` **sessionVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:10892](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10892)

#### Implementation of

[`ISessionStructure`](../interfaces/ISessionStructure.md).[`sessionVersion`](../interfaces/ISessionStructure.md#sessionversion)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10910](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10910)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:10905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10905)

#### Parameters

##### properties?

[`ISessionStructure`](../interfaces/ISessionStructure.md)

#### Returns

[`SessionStructure`](SessionStructure.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:10907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10907)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`SessionStructure`](SessionStructure.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10906](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10906)

#### Parameters

##### m

[`ISessionStructure`](../interfaces/ISessionStructure.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`SessionStructure`](SessionStructure.md)

Defined in: [WAProto/index.d.ts:10908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10908)

#### Parameters

##### d

#### Returns

[`SessionStructure`](SessionStructure.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10911](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10911)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10909](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10909)

#### Parameters

##### m

[`SessionStructure`](SessionStructure.md)

##### o?

`IConversionOptions`

#### Returns

`object`
