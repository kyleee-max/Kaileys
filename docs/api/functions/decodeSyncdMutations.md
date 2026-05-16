# Function: decodeSyncdMutations()

> **decodeSyncdMutations**(`msgMutations`, `initialState`, `getAppStateSyncKey`, `onMutation`, `validateMacs`): `Promise`\<\{ `hash`: `Buffer`\<`ArrayBuffer`\>; `indexValueMap`: \{\}; \}\>

Defined in: [src/Utils/chat-utils.ts:228](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L228)

## Parameters

### msgMutations

([`ISyncdMutation`](../namespaces/proto/interfaces/ISyncdMutation.md) \| [`ISyncdRecord`](../namespaces/proto/interfaces/ISyncdRecord.md))[]

### initialState

[`LTHashState`](../type-aliases/LTHashState.md)

### getAppStateSyncKey

`FetchAppStateSyncKey`

### onMutation

(`mutation`) => `void`

### validateMacs

`boolean`

## Returns

`Promise`\<\{ `hash`: `Buffer`\<`ArrayBuffer`\>; `indexValueMap`: \{\}; \}\>
