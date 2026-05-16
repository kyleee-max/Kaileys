# Class: BizAccountPayload

Defined in: [WAProto/index.d.ts:850](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L850)

## Implements

- [`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

## Constructors

### new BizAccountPayload()

> **new BizAccountPayload**(`p`?): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:851](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L851)

#### Parameters

##### p?

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

## Properties

### bizAcctLinkInfo?

> `optional` **bizAcctLinkInfo**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:853](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L853)

#### Implementation of

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md).[`bizAcctLinkInfo`](../interfaces/IBizAccountPayload.md#bizacctlinkinfo)

***

### vnameCert?

> `optional` **vnameCert**: `null` \| [`IVerifiedNameCertificate`](../interfaces/IVerifiedNameCertificate.md)

Defined in: [WAProto/index.d.ts:852](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L852)

#### Implementation of

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md).[`vnameCert`](../interfaces/IBizAccountPayload.md#vnamecert)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:859](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L859)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:854](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L854)

#### Parameters

##### properties?

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:856](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L856)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:855](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L855)

#### Parameters

##### m

[`IBizAccountPayload`](../interfaces/IBizAccountPayload.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BizAccountPayload`](BizAccountPayload.md)

Defined in: [WAProto/index.d.ts:857](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L857)

#### Parameters

##### d

#### Returns

[`BizAccountPayload`](BizAccountPayload.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:860](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L860)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:858](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L858)

#### Parameters

##### m

[`BizAccountPayload`](BizAccountPayload.md)

##### o?

`IConversionOptions`

#### Returns

`object`
