# Class: DNSSource

Defined in: [WAProto/index.d.ts:2754](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2754)

## Implements

- [`IDNSSource`](../interfaces/IDNSSource.md)

## Constructors

### new DNSSource()

> **new DNSSource**(`p`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:2755](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2755)

#### Parameters

##### p?

[`IDNSSource`](../interfaces/IDNSSource.md)

#### Returns

[`DNSSource`](DNSSource.md)

## Properties

### appCached?

> `optional` **appCached**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:2757](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2757)

#### Implementation of

[`IDNSSource`](../interfaces/IDNSSource.md).[`appCached`](../interfaces/IDNSSource.md#appcached)

***

### dnsMethod?

> `optional` **dnsMethod**: `null` \| [`DNSResolutionMethod`](../namespaces/DNSSource/enumerations/DNSResolutionMethod.md)

Defined in: [WAProto/index.d.ts:2756](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2756)

#### Implementation of

[`IDNSSource`](../interfaces/IDNSSource.md).[`dnsMethod`](../interfaces/IDNSSource.md#dnsmethod)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:2763](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2763)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:2758](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2758)

#### Parameters

##### properties?

[`IDNSSource`](../interfaces/IDNSSource.md)

#### Returns

[`DNSSource`](DNSSource.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:2760](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2760)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`DNSSource`](DNSSource.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:2759](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2759)

#### Parameters

##### m

[`IDNSSource`](../interfaces/IDNSSource.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`DNSSource`](DNSSource.md)

Defined in: [WAProto/index.d.ts:2761](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2761)

#### Parameters

##### d

#### Returns

[`DNSSource`](DNSSource.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:2764](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2764)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:2762](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L2762)

#### Parameters

##### m

[`DNSSource`](DNSSource.md)

##### o?

`IConversionOptions`

#### Returns

`object`
