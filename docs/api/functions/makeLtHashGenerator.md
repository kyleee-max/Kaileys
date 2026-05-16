# Function: makeLtHashGenerator()

> **makeLtHashGenerator**(`__namedParameters`): `object`

Defined in: [src/Utils/chat-utils.ts:77](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L77)

## Parameters

### \_\_namedParameters

`Pick`\<[`LTHashState`](../type-aliases/LTHashState.md), `"hash"` \| `"indexValueMap"`\>

## Returns

`object`

### finish()

> **finish**: () => `object`

#### Returns

`object`

##### hash

> **hash**: `Buffer`\<`ArrayBuffer`\>

##### indexValueMap

> **indexValueMap**: `object`

###### Index Signature

\[`indexMacBase64`: `string`\]: `object`

### mix()

> **mix**: (`__namedParameters`) => `void`

#### Parameters

##### \_\_namedParameters

`Mac`

#### Returns

`void`
