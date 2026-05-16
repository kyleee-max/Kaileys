# Class: AIHomeOption

Defined in: [WAProto/index.d.ts:152](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L152)

## Implements

- [`IAIHomeOption`](../interfaces/IAIHomeOption.md)

## Constructors

### new AIHomeOption()

> **new AIHomeOption**(`p`?): [`AIHomeOption`](AIHomeOption.md)

Defined in: [WAProto/index.d.ts:153](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L153)

#### Parameters

##### p?

[`IAIHomeOption`](../interfaces/IAIHomeOption.md)

#### Returns

[`AIHomeOption`](AIHomeOption.md)

## Properties

### imageBackgroundColor?

> `optional` **imageBackgroundColor**: `null` \| `string`

Defined in: [WAProto/index.d.ts:160](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L160)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`imageBackgroundColor`](../interfaces/IAIHomeOption.md#imagebackgroundcolor)

***

### imageTintColor?

> `optional` **imageTintColor**: `null` \| `string`

Defined in: [WAProto/index.d.ts:159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L159)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`imageTintColor`](../interfaces/IAIHomeOption.md#imagetintcolor)

***

### imageWdsIdentifier?

> `optional` **imageWdsIdentifier**: `null` \| `string`

Defined in: [WAProto/index.d.ts:158](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L158)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`imageWdsIdentifier`](../interfaces/IAIHomeOption.md#imagewdsidentifier)

***

### promptText?

> `optional` **promptText**: `null` \| `string`

Defined in: [WAProto/index.d.ts:156](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L156)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`promptText`](../interfaces/IAIHomeOption.md#prompttext)

***

### sessionId?

> `optional` **sessionId**: `null` \| `string`

Defined in: [WAProto/index.d.ts:157](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L157)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`sessionId`](../interfaces/IAIHomeOption.md#sessionid)

***

### title?

> `optional` **title**: `null` \| `string`

Defined in: [WAProto/index.d.ts:155](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L155)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`title`](../interfaces/IAIHomeOption.md#title)

***

### type?

> `optional` **type**: `null` \| [`AIHomeActionType`](../namespaces/AIHomeOption/enumerations/AIHomeActionType.md)

Defined in: [WAProto/index.d.ts:154](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L154)

#### Implementation of

[`IAIHomeOption`](../interfaces/IAIHomeOption.md).[`type`](../interfaces/IAIHomeOption.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:166](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L166)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AIHomeOption`](AIHomeOption.md)

Defined in: [WAProto/index.d.ts:161](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L161)

#### Parameters

##### properties?

[`IAIHomeOption`](../interfaces/IAIHomeOption.md)

#### Returns

[`AIHomeOption`](AIHomeOption.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AIHomeOption`](AIHomeOption.md)

Defined in: [WAProto/index.d.ts:163](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L163)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AIHomeOption`](AIHomeOption.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:162](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L162)

#### Parameters

##### m

[`IAIHomeOption`](../interfaces/IAIHomeOption.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AIHomeOption`](AIHomeOption.md)

Defined in: [WAProto/index.d.ts:164](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L164)

#### Parameters

##### d

#### Returns

[`AIHomeOption`](AIHomeOption.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:167](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L167)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:165](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L165)

#### Parameters

##### m

[`AIHomeOption`](AIHomeOption.md)

##### o?

`IConversionOptions`

#### Returns

`object`
