# Class: DetectedOutcomesStatusAction

Defined in: [WAProto/index.d.ts:11966](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11966)

## Implements

- [`IDetectedOutcomesStatusAction`](../interfaces/IDetectedOutcomesStatusAction.md)

## Constructors

### new DetectedOutcomesStatusAction()

> **new DetectedOutcomesStatusAction**(`p`?): [`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

Defined in: [WAProto/index.d.ts:11967](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11967)

#### Parameters

##### p?

[`IDetectedOutcomesStatusAction`](../interfaces/IDetectedOutcomesStatusAction.md)

#### Returns

[`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

## Properties

### isEnabled?

> `optional` **isEnabled**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11968](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11968)

#### Implementation of

[`IDetectedOutcomesStatusAction`](../interfaces/IDetectedOutcomesStatusAction.md).[`isEnabled`](../interfaces/IDetectedOutcomesStatusAction.md#isenabled)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11974](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11974)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

Defined in: [WAProto/index.d.ts:11969](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11969)

#### Parameters

##### properties?

[`IDetectedOutcomesStatusAction`](../interfaces/IDetectedOutcomesStatusAction.md)

#### Returns

[`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

Defined in: [WAProto/index.d.ts:11971](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11971)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11970](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11970)

#### Parameters

##### m

[`IDetectedOutcomesStatusAction`](../interfaces/IDetectedOutcomesStatusAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

Defined in: [WAProto/index.d.ts:11972](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11972)

#### Parameters

##### d

#### Returns

[`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11975](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11975)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11973](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11973)

#### Parameters

##### m

[`DetectedOutcomesStatusAction`](DetectedOutcomesStatusAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
