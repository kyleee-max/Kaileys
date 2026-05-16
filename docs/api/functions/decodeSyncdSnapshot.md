# Function: decodeSyncdSnapshot()

> **decodeSyncdSnapshot**(`name`, `snapshot`, `getAppStateSyncKey`, `minimumVersionNumber`, `validateMacs`, `logger`?): `Promise`\<\{ `mutationMap`: [`ChatMutationMap`](../type-aliases/ChatMutationMap.md); `state`: [`LTHashState`](../type-aliases/LTHashState.md); \}\>

Defined in: [src/Utils/chat-utils.ts:422](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L422)

## Parameters

### name

`"critical_unblock_low"` | `"regular_high"` | `"regular_low"` | `"critical_block"` | `"regular"`

### snapshot

[`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md)

### getAppStateSyncKey

`FetchAppStateSyncKey`

### minimumVersionNumber

`undefined` | `number`

### validateMacs

`boolean` = `true`

### logger?

`ILogger`

## Returns

`Promise`\<\{ `mutationMap`: [`ChatMutationMap`](../type-aliases/ChatMutationMap.md); `state`: [`LTHashState`](../type-aliases/LTHashState.md); \}\>
