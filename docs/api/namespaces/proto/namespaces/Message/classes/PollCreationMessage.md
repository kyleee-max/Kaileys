# Class: PollCreationMessage

Defined in: [WAProto/index.d.ts:8311](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8311)

## Implements

- [`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

## Constructors

### new PollCreationMessage()

> **new PollCreationMessage**(`p`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:8312](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8312)

#### Parameters

##### p?

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

## Properties

### contextInfo?

> `optional` **contextInfo**: `null` \| [`IContextInfo`](../../../interfaces/IContextInfo.md)

Defined in: [WAProto/index.d.ts:8317](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8317)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`contextInfo`](../interfaces/IPollCreationMessage.md#contextinfo)

***

### correctAnswer?

> `optional` **correctAnswer**: `null` \| [`IOption`](../namespaces/PollCreationMessage/interfaces/IOption.md)

Defined in: [WAProto/index.d.ts:8320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8320)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`correctAnswer`](../interfaces/IPollCreationMessage.md#correctanswer)

***

### encKey?

> `optional` **encKey**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8313](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8313)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`encKey`](../interfaces/IPollCreationMessage.md#enckey)

***

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8314](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8314)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`name`](../interfaces/IPollCreationMessage.md#name)

***

### options

> **options**: [`IOption`](../namespaces/PollCreationMessage/interfaces/IOption.md)[]

Defined in: [WAProto/index.d.ts:8315](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8315)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`options`](../interfaces/IPollCreationMessage.md#options)

***

### pollContentType?

> `optional` **pollContentType**: `null` \| [`PollContentType`](../enumerations/PollContentType.md)

Defined in: [WAProto/index.d.ts:8318](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8318)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`pollContentType`](../interfaces/IPollCreationMessage.md#pollcontenttype)

***

### pollType?

> `optional` **pollType**: `null` \| [`PollType`](../enumerations/PollType.md)

Defined in: [WAProto/index.d.ts:8319](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8319)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`pollType`](../interfaces/IPollCreationMessage.md#polltype)

***

### selectableOptionsCount?

> `optional` **selectableOptionsCount**: `null` \| `number`

Defined in: [WAProto/index.d.ts:8316](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8316)

#### Implementation of

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md).[`selectableOptionsCount`](../interfaces/IPollCreationMessage.md#selectableoptionscount)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8326](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8326)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:8321](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8321)

#### Parameters

##### properties?

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:8323](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8323)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8322](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8322)

#### Parameters

##### m

[`IPollCreationMessage`](../interfaces/IPollCreationMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PollCreationMessage`](PollCreationMessage.md)

Defined in: [WAProto/index.d.ts:8324](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8324)

#### Parameters

##### d

#### Returns

[`PollCreationMessage`](PollCreationMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8327](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8327)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8325](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8325)

#### Parameters

##### m

[`PollCreationMessage`](PollCreationMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
