# Function: extractSyncdPatches()

> **extractSyncdPatches**(`result`, `options`): `Promise`\<\{ `critical_block`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `critical_unblock_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_high`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; \}\>

Defined in: [src/Utils/chat-utils.ts:354](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L354)

## Parameters

### result

[`BinaryNode`](../type-aliases/BinaryNode.md)

### options

`RequestInit`

## Returns

`Promise`\<\{ `critical_block`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `critical_unblock_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_high`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; `regular_low`: \{ `hasMorePatches`: `boolean`; `patches`: [`ISyncdPatch`](../namespaces/proto/interfaces/ISyncdPatch.md)[]; `snapshot`: [`ISyncdSnapshot`](../namespaces/proto/interfaces/ISyncdSnapshot.md); \}; \}\>
