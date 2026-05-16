# Function: generateOrGetPreKeys()

> **generateOrGetPreKeys**(`creds`, `range`): `object`

Defined in: [src/Utils/signal.ts:53](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/signal.ts#L53)

## Parameters

### creds

[`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md)

### range

`number`

## Returns

`object`

### lastPreKeyId

> **lastPreKeyId**: `number`

### newPreKeys

> **newPreKeys**: `object`

#### Index Signature

\[`id`: `number`\]: [`KeyPair`](../type-aliases/KeyPair.md)

### preKeysRange

> **preKeysRange**: readonly \[`number`, `number`\]
