# Class: ActionLink

Defined in: [WAProto/index.d.ts:756](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L756)

## Implements

- [`IActionLink`](../interfaces/IActionLink.md)

## Constructors

### new ActionLink()

> **new ActionLink**(`p`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:757](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L757)

#### Parameters

##### p?

[`IActionLink`](../interfaces/IActionLink.md)

#### Returns

[`ActionLink`](ActionLink.md)

## Properties

### buttonTitle?

> `optional` **buttonTitle**: `null` \| `string`

Defined in: [WAProto/index.d.ts:759](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L759)

#### Implementation of

[`IActionLink`](../interfaces/IActionLink.md).[`buttonTitle`](../interfaces/IActionLink.md#buttontitle)

***

### url?

> `optional` **url**: `null` \| `string`

Defined in: [WAProto/index.d.ts:758](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L758)

#### Implementation of

[`IActionLink`](../interfaces/IActionLink.md).[`url`](../interfaces/IActionLink.md#url)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:765](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L765)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:760](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L760)

#### Parameters

##### properties?

[`IActionLink`](../interfaces/IActionLink.md)

#### Returns

[`ActionLink`](ActionLink.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:762](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L762)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ActionLink`](ActionLink.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:761](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L761)

#### Parameters

##### m

[`IActionLink`](../interfaces/IActionLink.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ActionLink`](ActionLink.md)

Defined in: [WAProto/index.d.ts:763](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L763)

#### Parameters

##### d

#### Returns

[`ActionLink`](ActionLink.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:766](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L766)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:764](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L764)

#### Parameters

##### m

[`ActionLink`](ActionLink.md)

##### o?

`IConversionOptions`

#### Returns

`object`
