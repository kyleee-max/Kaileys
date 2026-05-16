# Class: AppStateFatalExceptionNotification

Defined in: [WAProto/index.d.ts:5416](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5416)

## Implements

- [`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

## Constructors

### new AppStateFatalExceptionNotification()

> **new AppStateFatalExceptionNotification**(`p`?): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:5417](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5417)

#### Parameters

##### p?

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

## Properties

### collectionNames

> **collectionNames**: `string`[]

Defined in: [WAProto/index.d.ts:5418](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5418)

#### Implementation of

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md).[`collectionNames`](../interfaces/IAppStateFatalExceptionNotification.md#collectionnames)

***

### timestamp?

> `optional` **timestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:5419](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5419)

#### Implementation of

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md).[`timestamp`](../interfaces/IAppStateFatalExceptionNotification.md#timestamp)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:5425](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5425)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:5420](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5420)

#### Parameters

##### properties?

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:5422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5422)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:5421](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5421)

#### Parameters

##### m

[`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:5423](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5423)

#### Parameters

##### d

#### Returns

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:5426](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5426)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:5424](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L5424)

#### Parameters

##### m

[`AppStateFatalExceptionNotification`](AppStateFatalExceptionNotification.md)

##### o?

`IConversionOptions`

#### Returns

`object`
