# Class: PhoneNumberToLIDMapping

Defined in: [WAProto/index.d.ts:10297](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10297)

## Implements

- [`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

## Constructors

### new PhoneNumberToLIDMapping()

> **new PhoneNumberToLIDMapping**(`p`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:10298](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10298)

#### Parameters

##### p?

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

## Properties

### lidJid?

> `optional` **lidJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10300](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10300)

#### Implementation of

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md).[`lidJid`](../interfaces/IPhoneNumberToLIDMapping.md#lidjid)

***

### pnJid?

> `optional` **pnJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:10299](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10299)

#### Implementation of

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md).[`pnJid`](../interfaces/IPhoneNumberToLIDMapping.md#pnjid)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:10306](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10306)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:10301](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10301)

#### Parameters

##### properties?

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:10303](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10303)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:10302](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10302)

#### Parameters

##### m

[`IPhoneNumberToLIDMapping`](../interfaces/IPhoneNumberToLIDMapping.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

Defined in: [WAProto/index.d.ts:10304](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10304)

#### Parameters

##### d

#### Returns

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:10307](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10307)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:10305](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L10305)

#### Parameters

##### m

[`PhoneNumberToLIDMapping`](PhoneNumberToLIDMapping.md)

##### o?

`IConversionOptions`

#### Returns

`object`
