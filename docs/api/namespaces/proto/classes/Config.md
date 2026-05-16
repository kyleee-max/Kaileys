# Class: Config

Defined in: [WAProto/index.d.ts:3116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3116)

## Implements

- [`IConfig`](../interfaces/IConfig.md)

## Constructors

### new Config()

> **new Config**(`p`?): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:3117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3117)

#### Parameters

##### p?

[`IConfig`](../interfaces/IConfig.md)

#### Returns

[`Config`](Config.md)

## Properties

### field

> **field**: `object`

Defined in: [WAProto/index.d.ts:3118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3118)

#### Index Signature

\[`k`: `string`\]: [`IField`](../interfaces/IField.md)

#### Implementation of

[`IConfig`](../interfaces/IConfig.md).[`field`](../interfaces/IConfig.md#field)

***

### version?

> `optional` **version**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3119)

#### Implementation of

[`IConfig`](../interfaces/IConfig.md).[`version`](../interfaces/IConfig.md#version)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3125)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:3120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3120)

#### Parameters

##### properties?

[`IConfig`](../interfaces/IConfig.md)

#### Returns

[`Config`](Config.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:3122](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3122)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Config`](Config.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:3121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3121)

#### Parameters

##### m

[`IConfig`](../interfaces/IConfig.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Config`](Config.md)

Defined in: [WAProto/index.d.ts:3123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3123)

#### Parameters

##### d

#### Returns

[`Config`](Config.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3126)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3124)

#### Parameters

##### m

[`Config`](Config.md)

##### o?

`IConversionOptions`

#### Returns

`object`
