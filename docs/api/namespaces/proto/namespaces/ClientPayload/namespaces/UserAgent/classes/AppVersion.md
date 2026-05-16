# Class: AppVersion

Defined in: [WAProto/index.d.ts:2904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2904)

## Implements

- [`IAppVersion`](../interfaces/IAppVersion.md)

## Constructors

### new AppVersion()

> **new AppVersion**(`p`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:2905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2905)

#### Parameters

##### p?

[`IAppVersion`](../interfaces/IAppVersion.md)

#### Returns

[`AppVersion`](AppVersion.md)

## Properties

### primary?

> `optional` **primary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2906](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2906)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`primary`](../interfaces/IAppVersion.md#primary)

***

### quaternary?

> `optional` **quaternary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2909](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2909)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`quaternary`](../interfaces/IAppVersion.md#quaternary)

***

### quinary?

> `optional` **quinary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2910](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2910)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`quinary`](../interfaces/IAppVersion.md#quinary)

***

### secondary?

> `optional` **secondary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2907)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`secondary`](../interfaces/IAppVersion.md#secondary)

***

### tertiary?

> `optional` **tertiary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:2908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2908)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`tertiary`](../interfaces/IAppVersion.md#tertiary)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2916](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2916)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:2911](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2911)

#### Parameters

##### properties?

[`IAppVersion`](../interfaces/IAppVersion.md)

#### Returns

[`AppVersion`](AppVersion.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:2913](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2913)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppVersion`](AppVersion.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2912](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2912)

#### Parameters

##### m

[`IAppVersion`](../interfaces/IAppVersion.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:2914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2914)

#### Parameters

##### d

#### Returns

[`AppVersion`](AppVersion.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2917](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2917)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2915](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2915)

#### Parameters

##### m

[`AppVersion`](AppVersion.md)

##### o?

`IConversionOptions`

#### Returns

`object`
