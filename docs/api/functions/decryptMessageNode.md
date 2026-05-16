# Function: decryptMessageNode()

> **decryptMessageNode**(`stanza`, `meId`, `meLid`, `repository`, `logger`): `object`

Defined in: [src/Utils/decode-wa-message.ts:257](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/decode-wa-message.ts#L257)

## Parameters

### stanza

[`BinaryNode`](../type-aliases/BinaryNode.md)

### meId

`string`

### meLid

`string`

### repository

[`SignalRepositoryWithLIDStore`](../interfaces/SignalRepositoryWithLIDStore.md)

### logger

`ILogger`

## Returns

`object`

### author

> **author**: `string`

### category

> **category**: `undefined` \| `string` = `stanza.attrs.category`

### fullMessage

> **fullMessage**: [`WAMessage`](../type-aliases/WAMessage.md)

### decrypt()

#### Returns

`Promise`\<`void`\>
