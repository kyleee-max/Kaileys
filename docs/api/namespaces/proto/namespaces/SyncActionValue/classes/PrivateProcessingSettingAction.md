# Class: PrivateProcessingSettingAction

Defined in: [WAProto/index.d.ts:12609](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12609)

## Implements

- [`IPrivateProcessingSettingAction`](../interfaces/IPrivateProcessingSettingAction.md)

## Constructors

### new PrivateProcessingSettingAction()

> **new PrivateProcessingSettingAction**(`p`?): [`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

Defined in: [WAProto/index.d.ts:12610](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12610)

#### Parameters

##### p?

[`IPrivateProcessingSettingAction`](../interfaces/IPrivateProcessingSettingAction.md)

#### Returns

[`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

## Properties

### privateProcessingStatus?

> `optional` **privateProcessingStatus**: `null` \| [`PrivateProcessingStatus`](../namespaces/PrivateProcessingSettingAction/enumerations/PrivateProcessingStatus.md)

Defined in: [WAProto/index.d.ts:12611](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12611)

#### Implementation of

[`IPrivateProcessingSettingAction`](../interfaces/IPrivateProcessingSettingAction.md).[`privateProcessingStatus`](../interfaces/IPrivateProcessingSettingAction.md#privateprocessingstatus)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12617](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12617)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

Defined in: [WAProto/index.d.ts:12612](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12612)

#### Parameters

##### properties?

[`IPrivateProcessingSettingAction`](../interfaces/IPrivateProcessingSettingAction.md)

#### Returns

[`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

Defined in: [WAProto/index.d.ts:12614](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12614)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12613](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12613)

#### Parameters

##### m

[`IPrivateProcessingSettingAction`](../interfaces/IPrivateProcessingSettingAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

Defined in: [WAProto/index.d.ts:12615](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12615)

#### Parameters

##### d

#### Returns

[`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12618](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12618)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12616](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12616)

#### Parameters

##### m

[`PrivateProcessingSettingAction`](PrivateProcessingSettingAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
