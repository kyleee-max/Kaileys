# Class: Field

Defined in: [WAProto/index.d.ts:4244](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4244)

## Implements

- [`IField`](../interfaces/IField.md)

## Constructors

### new Field()

> **new Field**(`p`?): [`Field`](Field.md)

Defined in: [WAProto/index.d.ts:4245](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4245)

#### Parameters

##### p?

[`IField`](../interfaces/IField.md)

#### Returns

[`Field`](Field.md)

## Properties

### isMessage?

> `optional` **isMessage**: `null` \| `boolean`

Defined in: [WAProto/index.d.ts:4249](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4249)

#### Implementation of

[`IField`](../interfaces/IField.md).[`isMessage`](../interfaces/IField.md#ismessage)

***

### maxVersion?

> `optional` **maxVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4247](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4247)

#### Implementation of

[`IField`](../interfaces/IField.md).[`maxVersion`](../interfaces/IField.md#maxversion)

***

### minVersion?

> `optional` **minVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4246](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4246)

#### Implementation of

[`IField`](../interfaces/IField.md).[`minVersion`](../interfaces/IField.md#minversion)

***

### notReportableMinVersion?

> `optional` **notReportableMinVersion**: `null` \| `number`

Defined in: [WAProto/index.d.ts:4248](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4248)

#### Implementation of

[`IField`](../interfaces/IField.md).[`notReportableMinVersion`](../interfaces/IField.md#notreportableminversion)

***

### subfield

> **subfield**: `object`

Defined in: [WAProto/index.d.ts:4250](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4250)

#### Index Signature

\[`k`: `string`\]: [`IField`](../interfaces/IField.md)

#### Implementation of

[`IField`](../interfaces/IField.md).[`subfield`](../interfaces/IField.md#subfield)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:4256](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4256)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`Field`](Field.md)

Defined in: [WAProto/index.d.ts:4251](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4251)

#### Parameters

##### properties?

[`IField`](../interfaces/IField.md)

#### Returns

[`Field`](Field.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`Field`](Field.md)

Defined in: [WAProto/index.d.ts:4253](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4253)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`Field`](Field.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:4252](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4252)

#### Parameters

##### m

[`IField`](../interfaces/IField.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`Field`](Field.md)

Defined in: [WAProto/index.d.ts:4254](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4254)

#### Parameters

##### d

#### Returns

[`Field`](Field.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:4257](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4257)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:4255](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L4255)

#### Parameters

##### m

[`Field`](Field.md)

##### o?

`IConversionOptions`

#### Returns

`object`
