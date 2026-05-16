# Class: OrderMessage

Defined in: [WAProto/index.d.ts:7577](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7577)

## Implements

- [`IOrderMessage`](../interfaces/IOrderMessage.md)

## Constructors

### new OrderMessage()

> **new OrderMessage**(`p`?): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:7578](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7578)

#### Parameters

##### p?

[`IOrderMessage`](../interfaces/IOrderMessage.md)

#### Returns

[`OrderMessage`](OrderMessage.md)

## Properties

### catalogType?

> `optional` **catalogType**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7593)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`catalogType`](../interfaces/IOrderMessage.md#catalogtype)

***

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:7590](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7590)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`contextInfo`](../interfaces/IOrderMessage.md#contextinfo)

***

### itemCount?

> `optional` **itemCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7581](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7581)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`itemCount`](../interfaces/IOrderMessage.md#itemcount)

***

### message?

> `optional` **message**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7584](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7584)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`message`](../interfaces/IOrderMessage.md#message)

***

### messageVersion?

> `optional` **messageVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:7591](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7591)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`messageVersion`](../interfaces/IOrderMessage.md#messageversion)

***

### orderId?

> `optional` **orderId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7579](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7579)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`orderId`](../interfaces/IOrderMessage.md#orderid)

***

### orderRequestMessageId?

> `optional` **orderRequestMessageId**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:7592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7592)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`orderRequestMessageId`](../interfaces/IOrderMessage.md#orderrequestmessageid)

***

### orderTitle?

> `optional` **orderTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7585](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7585)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`orderTitle`](../interfaces/IOrderMessage.md#ordertitle)

***

### sellerJid?

> `optional` **sellerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7586](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7586)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`sellerJid`](../interfaces/IOrderMessage.md#sellerjid)

***

### status?

> `optional` **status**: `null` \| [`OrderStatus`](../namespaces/OrderMessage/enumerations/OrderStatus.md)

Defined in: [WAProto/index.d.ts:7582](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7582)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`status`](../interfaces/IOrderMessage.md#status)

***

### surface?

> `optional` **surface**: `null` \| [`CATALOG`](../namespaces/OrderMessage/enumerations/OrderSurface.md#catalog)

Defined in: [WAProto/index.d.ts:7583](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7583)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`surface`](../interfaces/IOrderMessage.md#surface)

***

### thumbnail?

> `optional` **thumbnail**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:7580](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7580)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`thumbnail`](../interfaces/IOrderMessage.md#thumbnail)

***

### token?

> `optional` **token**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7587](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7587)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`token`](../interfaces/IOrderMessage.md#token)

***

### totalAmount1000?

> `optional` **totalAmount1000**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:7588](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7588)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`totalAmount1000`](../interfaces/IOrderMessage.md#totalamount1000)

***

### totalCurrencyCode?

> `optional` **totalCurrencyCode**: `null` \| `string`

Defined in: [WAProto/index.d.ts:7589](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7589)

#### Implementation of

[`IOrderMessage`](../interfaces/IOrderMessage.md).[`totalCurrencyCode`](../interfaces/IOrderMessage.md#totalcurrencycode)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:7599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7599)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:7594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7594)

#### Parameters

##### properties?

[`IOrderMessage`](../interfaces/IOrderMessage.md)

#### Returns

[`OrderMessage`](OrderMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:7596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7596)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`OrderMessage`](OrderMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:7595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7595)

#### Parameters

##### m

[`IOrderMessage`](../interfaces/IOrderMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`OrderMessage`](OrderMessage.md)

Defined in: [WAProto/index.d.ts:7597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7597)

#### Parameters

##### d

#### Returns

[`OrderMessage`](OrderMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:7600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7600)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:7598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L7598)

#### Parameters

##### m

[`OrderMessage`](OrderMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
