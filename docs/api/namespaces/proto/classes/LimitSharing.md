# Class: LimitSharing

Defined in: [WAProto/index.d.ts:5028](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5028)

## Implements

- [`ILimitSharing`](../interfaces/ILimitSharing.md)

## Constructors

### new LimitSharing()

> **new LimitSharing**(`p`?): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:5029](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5029)

#### Parameters

##### p?

[`ILimitSharing`](../interfaces/ILimitSharing.md)

#### Returns

[`LimitSharing`](LimitSharing.md)

## Properties

### initiatedByMe?

> `optional` **initiatedByMe**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:5033](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5033)

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`initiatedByMe`](../interfaces/ILimitSharing.md#initiatedbyme)

***

### limitSharingSettingTimestamp?

> `optional` **limitSharingSettingTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5032](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5032)

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`limitSharingSettingTimestamp`](../interfaces/ILimitSharing.md#limitsharingsettingtimestamp)

***

### sharingLimited?

> `optional` **sharingLimited**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:5030](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5030)

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`sharingLimited`](../interfaces/ILimitSharing.md#sharinglimited)

***

### trigger?

> `optional` **trigger**: `null` \| [`TriggerType`](../namespaces/LimitSharing/enumerations/TriggerType.md)

Defined in: [WAProto/index.d.ts:5031](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5031)

#### Implementation of

[`ILimitSharing`](../interfaces/ILimitSharing.md).[`trigger`](../interfaces/ILimitSharing.md#trigger)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5039)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:5034](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5034)

#### Parameters

##### properties?

[`ILimitSharing`](../interfaces/ILimitSharing.md)

#### Returns

[`LimitSharing`](LimitSharing.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:5036](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5036)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`LimitSharing`](LimitSharing.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5035](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5035)

#### Parameters

##### m

[`ILimitSharing`](../interfaces/ILimitSharing.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`LimitSharing`](LimitSharing.md)

Defined in: [WAProto/index.d.ts:5037](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5037)

#### Parameters

##### d

#### Returns

[`LimitSharing`](LimitSharing.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5040)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5038)

#### Parameters

##### m

[`LimitSharing`](LimitSharing.md)

##### o?

`IConversionOptions`

#### Returns

`object`
