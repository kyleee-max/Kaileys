# Class: StatusAttribution

Defined in: [WAProto/index.d.ts:11112](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11112)

## Implements

- [`IStatusAttribution`](../interfaces/IStatusAttribution.md)

## Constructors

### new StatusAttribution()

> **new StatusAttribution**(`p`?): [`StatusAttribution`](StatusAttribution.md)

Defined in: [WAProto/index.d.ts:11113](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11113)

#### Parameters

##### p?

[`IStatusAttribution`](../interfaces/IStatusAttribution.md)

#### Returns

[`StatusAttribution`](StatusAttribution.md)

## Properties

### actionUrl?

> `optional` **actionUrl**: `null` \| `string`

Defined in: [WAProto/index.d.ts:11115](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11115)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`actionUrl`](../interfaces/IStatusAttribution.md#actionurl)

***

### aiCreatedAttribution?

> `optional` **aiCreatedAttribution**: `null` \| [`IAiCreatedAttribution`](../namespaces/StatusAttribution/interfaces/IAiCreatedAttribution.md)

Defined in: [WAProto/index.d.ts:11121](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11121)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`aiCreatedAttribution`](../interfaces/IStatusAttribution.md#aicreatedattribution)

***

### attributionData?

> `optional` **attributionData**: `"statusReshare"` \| `"externalShare"` \| `"music"` \| `"groupStatus"` \| `"rlAttribution"` \| `"aiCreatedAttribution"`

Defined in: [WAProto/index.d.ts:11122](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11122)

***

### externalShare?

> `optional` **externalShare**: `null` \| [`IExternalShare`](../namespaces/StatusAttribution/interfaces/IExternalShare.md)

Defined in: [WAProto/index.d.ts:11117](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11117)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`externalShare`](../interfaces/IStatusAttribution.md#externalshare)

***

### groupStatus?

> `optional` **groupStatus**: `null` \| [`IGroupStatus`](../namespaces/StatusAttribution/interfaces/IGroupStatus.md)

Defined in: [WAProto/index.d.ts:11119](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11119)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`groupStatus`](../interfaces/IStatusAttribution.md#groupstatus)

***

### music?

> `optional` **music**: `null` \| [`IMusic`](../namespaces/StatusAttribution/interfaces/IMusic.md)

Defined in: [WAProto/index.d.ts:11118](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11118)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`music`](../interfaces/IStatusAttribution.md#music)

***

### rlAttribution?

> `optional` **rlAttribution**: `null` \| [`IRLAttribution`](../namespaces/StatusAttribution/interfaces/IRLAttribution.md)

Defined in: [WAProto/index.d.ts:11120](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11120)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`rlAttribution`](../interfaces/IStatusAttribution.md#rlattribution)

***

### statusReshare?

> `optional` **statusReshare**: `null` \| [`IStatusReshare`](../namespaces/StatusAttribution/interfaces/IStatusReshare.md)

Defined in: [WAProto/index.d.ts:11116](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11116)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`statusReshare`](../interfaces/IStatusAttribution.md#statusreshare)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/StatusAttribution/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:11114](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11114)

#### Implementation of

[`IStatusAttribution`](../interfaces/IStatusAttribution.md).[`type`](../interfaces/IStatusAttribution.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:11128](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11128)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`StatusAttribution`](StatusAttribution.md)

Defined in: [WAProto/index.d.ts:11123](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11123)

#### Parameters

##### properties?

[`IStatusAttribution`](../interfaces/IStatusAttribution.md)

#### Returns

[`StatusAttribution`](StatusAttribution.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`StatusAttribution`](StatusAttribution.md)

Defined in: [WAProto/index.d.ts:11125](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11125)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`StatusAttribution`](StatusAttribution.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:11124](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11124)

#### Parameters

##### m

[`IStatusAttribution`](../interfaces/IStatusAttribution.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`StatusAttribution`](StatusAttribution.md)

Defined in: [WAProto/index.d.ts:11126](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11126)

#### Parameters

##### d

#### Returns

[`StatusAttribution`](StatusAttribution.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:11129](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11129)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:11127](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L11127)

#### Parameters

##### m

[`StatusAttribution`](StatusAttribution.md)

##### o?

`IConversionOptions`

#### Returns

`object`
