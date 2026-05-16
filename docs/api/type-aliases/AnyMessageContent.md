# Type Alias: AnyMessageContent

> **AnyMessageContent**: [`AnyRegularMessageContent`](AnyRegularMessageContent.md) \| \{ `force`: `boolean`; `forward`: [`WAMessage`](WAMessage.md); \} \| \{ `delete`: [`WAMessageKey`](WAMessageKey.md); \} \| \{ `disappearingMessagesInChat`: `boolean` \| `number`; \} \| \{ `limitSharing`: `boolean`; \}

Defined in: [src/Types/Message.ts:289](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Message.ts#L289)

## Type declaration

[`AnyRegularMessageContent`](AnyRegularMessageContent.md)

\{ `force`: `boolean`; `forward`: [`WAMessage`](WAMessage.md); \}

### force?

> `optional` **force**: `boolean`

### forward

> **forward**: [`WAMessage`](WAMessage.md)

\{ `delete`: [`WAMessageKey`](WAMessageKey.md); \}

### delete

> **delete**: [`WAMessageKey`](WAMessageKey.md)

Delete your message or anyone's message in a group (admin required)

\{ `disappearingMessagesInChat`: `boolean` \| `number`; \}

### disappearingMessagesInChat

> **disappearingMessagesInChat**: `boolean` \| `number`

\{ `limitSharing`: `boolean`; \}

### limitSharing

> **limitSharing**: `boolean`
