# Class: DeleteIndividualCallLogAction

Defined in: [WAProto/index.d.ts:11931](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11931)

## Implements

- [`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

## Constructors

### new DeleteIndividualCallLogAction()

> **new DeleteIndividualCallLogAction**(`p`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:11932](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11932)

#### Parameters

##### p?

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

## Properties

### isIncoming?

> `optional` **isIncoming**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:11934](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11934)

#### Implementation of

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md).[`isIncoming`](../interfaces/IDeleteIndividualCallLogAction.md#isincoming)

***

### peerJid?

> `optional` **peerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11933](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11933)

#### Implementation of

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md).[`peerJid`](../interfaces/IDeleteIndividualCallLogAction.md#peerjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11940](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11940)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:11935](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11935)

#### Parameters

##### properties?

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:11937](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11937)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11936](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11936)

#### Parameters

##### m

[`IDeleteIndividualCallLogAction`](../interfaces/IDeleteIndividualCallLogAction.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

Defined in: [WAProto/index.d.ts:11938](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11938)

#### Parameters

##### d

#### Returns

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11941](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11941)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11939](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11939)

#### Parameters

##### m

[`DeleteIndividualCallLogAction`](DeleteIndividualCallLogAction.md)

##### o?

`IConversionOptions`

#### Returns

`object`
