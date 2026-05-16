# Class: Call

Defined in: [WAProto/index.d.ts:5770](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5770)

## Implements

- [`ICall`](../interfaces/ICall.md)

## Constructors

### new Call()

> **new Call**(`p`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:5771](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5771)

#### Parameters

##### p?

[`ICall`](../interfaces/ICall.md)

#### Returns

[`Call`](Call.md)

## Properties

### callKey?

> `optional` **callKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5772](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5772)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`callKey`](../interfaces/ICall.md#callkey)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:5778](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5778)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`contextInfo`](../interfaces/ICall.md#contextinfo)

***

### conversionData?

> `optional` **conversionData**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5774](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5774)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionData`](../interfaces/ICall.md#conversiondata)

***

### conversionDelaySeconds?

> `optional` **conversionDelaySeconds**: `null` \| `number`

Defined in: [WAProto/index.d.ts:5775](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5775)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionDelaySeconds`](../interfaces/ICall.md#conversiondelayseconds)

***

### conversionSource?

> `optional` **conversionSource**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5773](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5773)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`conversionSource`](../interfaces/ICall.md#conversionsource)

***

### ctwaPayload?

> `optional` **ctwaPayload**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:5777](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5777)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`ctwaPayload`](../interfaces/ICall.md#ctwapayload)

***

### ctwaSignals?

> `optional` **ctwaSignals**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5776](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5776)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`ctwaSignals`](../interfaces/ICall.md#ctwasignals)

***

### deeplinkPayload?

> `optional` **deeplinkPayload**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5780](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5780)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`deeplinkPayload`](../interfaces/ICall.md#deeplinkpayload)

***

### nativeFlowCallButtonPayload?

> `optional` **nativeFlowCallButtonPayload**: `null` \| `string`

Defined in: [WAProto/index.d.ts:5779](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5779)

#### Implementation of

[`ICall`](../interfaces/ICall.md).[`nativeFlowCallButtonPayload`](../interfaces/ICall.md#nativeflowcallbuttonpayload)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5786](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5786)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:5781](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5781)

#### Parameters

##### properties?

[`ICall`](../interfaces/ICall.md)

#### Returns

[`Call`](Call.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:5783](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5783)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Call`](Call.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5782](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5782)

#### Parameters

##### m

[`ICall`](../interfaces/ICall.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Call`](Call.md)

Defined in: [WAProto/index.d.ts:5784](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5784)

#### Parameters

##### d

#### Returns

[`Call`](Call.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5787](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5787)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5785](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5785)

#### Parameters

##### m

[`Call`](Call.md)

##### o?

`IConversionOptions`

#### Returns

`object`
