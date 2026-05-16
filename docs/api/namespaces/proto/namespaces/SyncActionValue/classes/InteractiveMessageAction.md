# Class: InteractiveMessageAction

Defined in: [WAProto/index.d.ts:12033](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12033)

## Implements

- [`IInteractiveMessageAction`](../interfaces/IInteractiveMessageAction.md)

## Constructors

### new InteractiveMessageAction()

> **new InteractiveMessageAction**(`p`?): [`InteractiveMessageAction`](InteractiveMessageAction.md)

Defined in: [WAProto/index.d.ts:12034](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12034)

#### Parameters

##### p?

[`IInteractiveMessageAction`](../interfaces/IInteractiveMessageAction.md)

#### Returns

[`InteractiveMessageAction`](InteractiveMessageAction.md)

## Properties

### type

> **type**: [`DISABLE_CTA`](../namespaces/InteractiveMessageAction/enumerations/InteractiveMessageActionMode.md#disable_cta)

Defined in: [WAProto/index.d.ts:12035](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12035)

#### Implementation of

[`IInteractiveMessageAction`](../interfaces/IInteractiveMessageAction.md).[`type`](../interfaces/IInteractiveMessageAction.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:12041](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12041)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`InteractiveMessageAction`](InteractiveMessageAction.md)

Defined in: [WAProto/index.d.ts:12036](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12036)

#### Parameters

##### properties?

[`IInteractiveMessageAction`](../interfaces/IInteractiveMessageAction.md)

#### Returns

[`InteractiveMessageAction`](InteractiveMessageAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`InteractiveMessageAction`](InteractiveMessageAction.md)

Defined in: [WAProto/index.d.ts:12038](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12038)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`InteractiveMessageAction`](InteractiveMessageAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:12037](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12037)

#### Parameters

##### m

[`IInteractiveMessageAction`](../interfaces/IInteractiveMessageAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`InteractiveMessageAction`](InteractiveMessageAction.md)

Defined in: [WAProto/index.d.ts:12039](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12039)

#### Parameters

##### d

#### Returns

[`InteractiveMessageAction`](InteractiveMessageAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:12042](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12042)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:12040](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L12040)

#### Parameters

##### m

[`InteractiveMessageAction`](InteractiveMessageAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
