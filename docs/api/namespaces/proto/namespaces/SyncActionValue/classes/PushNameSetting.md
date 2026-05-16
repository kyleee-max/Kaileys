# Class: PushNameSetting

Defined in: [WAProto/index.d.ts:12634](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12634)

## Implements

- [`IPushNameSetting`](../interfaces/IPushNameSetting.md)

## Constructors

### new PushNameSetting()

> **new PushNameSetting**(`p`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:12635](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12635)

#### Parameters

##### p?

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

#### Returns

[`PushNameSetting`](PushNameSetting.md)

## Properties

### name?

> `optional` **name**: `null` \| `string`

Defined in: [WAProto/index.d.ts:12636](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12636)

#### Implementation of

[`IPushNameSetting`](../interfaces/IPushNameSetting.md).[`name`](../interfaces/IPushNameSetting.md#name)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12642](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12642)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:12637](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12637)

#### Parameters

##### properties?

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

#### Returns

[`PushNameSetting`](PushNameSetting.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:12639](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12639)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PushNameSetting`](PushNameSetting.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12638](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12638)

#### Parameters

##### m

[`IPushNameSetting`](../interfaces/IPushNameSetting.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PushNameSetting`](PushNameSetting.md)

Defined in: [WAProto/index.d.ts:12640](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12640)

#### Parameters

##### d

#### Returns

[`PushNameSetting`](PushNameSetting.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12643](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12643)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12641](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12641)

#### Parameters

##### m

[`PushNameSetting`](PushNameSetting.md)

##### o?

`IConversionOptions`

#### Returns

`object`
