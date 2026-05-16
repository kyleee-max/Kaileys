# Class: AIRichResponseUnifiedResponse

Defined in: [WAProto/index.d.ts:655](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L655)

## Implements

- [`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

## Constructors

### new AIRichResponseUnifiedResponse()

> **new AIRichResponseUnifiedResponse**(`p`?): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:656](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L656)

#### Parameters

##### p?

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

## Properties

### data?

> `optional` **data**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:657](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L657)

#### Implementation of

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md).[`data`](../interfaces/IAIRichResponseUnifiedResponse.md#data)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:663](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L663)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:658](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L658)

#### Parameters

##### properties?

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:660](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L660)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:659](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L659)

#### Parameters

##### m

[`IAIRichResponseUnifiedResponse`](../interfaces/IAIRichResponseUnifiedResponse.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

Defined in: [WAProto/index.d.ts:661](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L661)

#### Parameters

##### d

#### Returns

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:664](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L664)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:662](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L662)

#### Parameters

##### m

[`AIRichResponseUnifiedResponse`](AIRichResponseUnifiedResponse.md)

##### o?

`IConversionOptions`

#### Returns

`object`
