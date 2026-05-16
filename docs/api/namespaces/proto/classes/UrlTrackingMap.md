# Class: UrlTrackingMap

Defined in: [WAProto/index.d.ts:13283](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13283)

## Implements

- [`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

## Constructors

### new UrlTrackingMap()

> **new UrlTrackingMap**(`p`?): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:13284](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13284)

#### Parameters

##### p?

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

## Properties

### urlTrackingMapElements

> **urlTrackingMapElements**: [`IUrlTrackingMapElement`](../namespaces/UrlTrackingMap/interfaces/IUrlTrackingMapElement.md)[]

Defined in: [WAProto/index.d.ts:13285](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13285)

#### Implementation of

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md).[`urlTrackingMapElements`](../interfaces/IUrlTrackingMap.md#urltrackingmapelements)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:13291](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13291)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:13286](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13286)

#### Parameters

##### properties?

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:13288](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13288)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:13287](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13287)

#### Parameters

##### m

[`IUrlTrackingMap`](../interfaces/IUrlTrackingMap.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`UrlTrackingMap`](UrlTrackingMap.md)

Defined in: [WAProto/index.d.ts:13289](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13289)

#### Parameters

##### d

#### Returns

[`UrlTrackingMap`](UrlTrackingMap.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:13292](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13292)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:13290](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L13290)

#### Parameters

##### m

[`UrlTrackingMap`](UrlTrackingMap.md)

##### o?

`IConversionOptions`

#### Returns

`object`
