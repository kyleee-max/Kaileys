# Class: ExitCode

Defined in: [WAProto/index.d.ts:4197](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4197)

## Implements

- [`IExitCode`](../interfaces/IExitCode.md)

## Constructors

### new ExitCode()

> **new ExitCode**(`p`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:4198](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4198)

#### Parameters

##### p?

[`IExitCode`](../interfaces/IExitCode.md)

#### Returns

[`ExitCode`](ExitCode.md)

## Properties

### code?

> `optional` **code**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:4199](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4199)

#### Implementation of

[`IExitCode`](../interfaces/IExitCode.md).[`code`](../interfaces/IExitCode.md#code)

***

### text?

> `optional` **text**: `null` \| `string`

Defined in: [WAProto/index.d.ts:4200](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4200)

#### Implementation of

[`IExitCode`](../interfaces/IExitCode.md).[`text`](../interfaces/IExitCode.md#text)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4206](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4206)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:4201](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4201)

#### Parameters

##### properties?

[`IExitCode`](../interfaces/IExitCode.md)

#### Returns

[`ExitCode`](ExitCode.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:4203](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4203)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ExitCode`](ExitCode.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4202](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4202)

#### Parameters

##### m

[`IExitCode`](../interfaces/IExitCode.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ExitCode`](ExitCode.md)

Defined in: [WAProto/index.d.ts:4204](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4204)

#### Parameters

##### d

#### Returns

[`ExitCode`](ExitCode.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4207](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4207)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4205](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4205)

#### Parameters

##### m

[`ExitCode`](ExitCode.md)

##### o?

`IConversionOptions`

#### Returns

`object`
