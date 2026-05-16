# Class: BizAccountLinkInfo

Defined in: [WAProto/index.d.ts:817](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L817)

## Implements

- [`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

## Constructors

### new BizAccountLinkInfo()

> **new BizAccountLinkInfo**(`p`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:818](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L818)

#### Parameters

##### p?

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

## Properties

### accountType?

> `optional` **accountType**: `null` \| [`ENTERPRISE`](../namespaces/BizAccountLinkInfo/enumerations/AccountType.md#enterprise)

Defined in: [WAProto/index.d.ts:823](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L823)

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`accountType`](../interfaces/IBizAccountLinkInfo.md#accounttype)

***

### hostStorage?

> `optional` **hostStorage**: `null` \| [`HostStorageType`](../namespaces/BizAccountLinkInfo/enumerations/HostStorageType.md)

Defined in: [WAProto/index.d.ts:822](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L822)

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`hostStorage`](../interfaces/IBizAccountLinkInfo.md#hoststorage)

***

### issueTime?

> `optional` **issueTime**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:821](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L821)

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`issueTime`](../interfaces/IBizAccountLinkInfo.md#issuetime)

***

### whatsappAcctNumber?

> `optional` **whatsappAcctNumber**: `null` \| `string`

Defined in: [WAProto/index.d.ts:820](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L820)

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`whatsappAcctNumber`](../interfaces/IBizAccountLinkInfo.md#whatsappacctnumber)

***

### whatsappBizAcctFbid?

> `optional` **whatsappBizAcctFbid**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:819](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L819)

#### Implementation of

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md).[`whatsappBizAcctFbid`](../interfaces/IBizAccountLinkInfo.md#whatsappbizacctfbid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:829](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L829)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:824](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L824)

#### Parameters

##### properties?

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:826](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L826)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:825](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L825)

#### Parameters

##### m

[`IBizAccountLinkInfo`](../interfaces/IBizAccountLinkInfo.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BizAccountLinkInfo`](BizAccountLinkInfo.md)

Defined in: [WAProto/index.d.ts:827](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L827)

#### Parameters

##### d

#### Returns

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:830](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L830)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:828](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L828)

#### Parameters

##### m

[`BizAccountLinkInfo`](BizAccountLinkInfo.md)

##### o?

`IConversionOptions`

#### Returns

`object`
