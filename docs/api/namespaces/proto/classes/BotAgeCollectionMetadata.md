# Class: BotAgeCollectionMetadata

Defined in: [WAProto/index.d.ts:918](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L918)

## Implements

- [`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

## Constructors

### new BotAgeCollectionMetadata()

> **new BotAgeCollectionMetadata**(`p`?): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:919](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L919)

#### Parameters

##### p?

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

## Properties

### ageCollectionEligible?

> `optional` **ageCollectionEligible**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:920](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L920)

#### Implementation of

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md).[`ageCollectionEligible`](../interfaces/IBotAgeCollectionMetadata.md#agecollectioneligible)

***

### ageCollectionType?

> `optional` **ageCollectionType**: `null` \| [`AgeCollectionType`](../namespaces/BotAgeCollectionMetadata/enumerations/AgeCollectionType.md)

Defined in: [WAProto/index.d.ts:922](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L922)

#### Implementation of

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md).[`ageCollectionType`](../interfaces/IBotAgeCollectionMetadata.md#agecollectiontype)

***

### shouldTriggerAgeCollectionOnClient?

> `optional` **shouldTriggerAgeCollectionOnClient**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:921](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L921)

#### Implementation of

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md).[`shouldTriggerAgeCollectionOnClient`](../interfaces/IBotAgeCollectionMetadata.md#shouldtriggeragecollectiononclient)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:928](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L928)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:923](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L923)

#### Parameters

##### properties?

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:925](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L925)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:924](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L924)

#### Parameters

##### m

[`IBotAgeCollectionMetadata`](../interfaces/IBotAgeCollectionMetadata.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

Defined in: [WAProto/index.d.ts:926](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L926)

#### Parameters

##### d

#### Returns

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:929](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L929)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:927](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L927)

#### Parameters

##### m

[`BotAgeCollectionMetadata`](BotAgeCollectionMetadata.md)

##### o?

`IConversionOptions`

#### Returns

`object`
