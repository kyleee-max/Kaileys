# Class: AppVersion

Defined in: [WAProto/index.d.ts:3901](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3901)

## Implements

- [`IAppVersion`](../interfaces/IAppVersion.md)

## Constructors

### new AppVersion()

> **new AppVersion**(`p`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:3902](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3902)

#### Parameters

##### p?

[`IAppVersion`](../interfaces/IAppVersion.md)

#### Returns

[`AppVersion`](AppVersion.md)

## Properties

### primary?

> `optional` **primary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3903](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3903)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`primary`](../interfaces/IAppVersion.md#primary)

***

### quaternary?

> `optional` **quaternary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3906](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3906)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`quaternary`](../interfaces/IAppVersion.md#quaternary)

***

### quinary?

> `optional` **quinary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3907](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3907)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`quinary`](../interfaces/IAppVersion.md#quinary)

***

### secondary?

> `optional` **secondary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3904](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3904)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`secondary`](../interfaces/IAppVersion.md#secondary)

***

### tertiary?

> `optional` **tertiary**: `null` \| `number`

Defined in: [WAProto/index.d.ts:3905](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3905)

#### Implementation of

[`IAppVersion`](../interfaces/IAppVersion.md).[`tertiary`](../interfaces/IAppVersion.md#tertiary)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:3913](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3913)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:3908](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3908)

#### Parameters

##### properties?

[`IAppVersion`](../interfaces/IAppVersion.md)

#### Returns

[`AppVersion`](AppVersion.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppVersion`](AppVersion.md)

Defined in: [WAProto/index.d.ts:3910](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3910)

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

Defined in: [WAProto/index.d.ts:3909](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3909)

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

Defined in: [WAProto/index.d.ts:3911](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3911)

#### Parameters

##### d

#### Returns

[`AppVersion`](AppVersion.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:3914](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3914)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:3912](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L3912)

#### Parameters

##### m

[`AppVersion`](AppVersion.md)

##### o?

`IConversionOptions`

#### Returns

`object`
