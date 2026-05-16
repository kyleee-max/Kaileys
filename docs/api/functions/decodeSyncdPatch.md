# Function: decodeSyncdPatch()

> **decodeSyncdPatch**(`msg`, `name`, `initialState`, `getAppStateSyncKey`, `onMutation`, `validateMacs`): `Promise`\<\{ `hash`: `Buffer`\<`ArrayBuffer`\>; `indexValueMap`: \{\}; \}\>

Defined in: [src/Utils/chat-utils.ts:320](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L320)

## Parameters

### msg

[`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)

### name

`"critical_unblock_low"` | `"regular_high"` | `"regular_low"` | `"critical_block"` | `"regular"`

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
