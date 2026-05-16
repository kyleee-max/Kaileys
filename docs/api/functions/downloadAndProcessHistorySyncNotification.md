# Function: downloadAndProcessHistorySyncNotification()

> **downloadAndProcessHistorySyncNotification**(`msg`, `options`, `logger`?): `Promise`\<\{ `chats`: [`Chat`](../type-aliases/Chat.md)[]; `contacts`: [`Contact`](../interfaces/Contact.md)[]; `lidPnMappings`: [`LIDMapping`](../type-aliases/LIDMapping.md)[]; `messages`: [`WAMessage`](../type-aliases/WAMessage.md)[]; `pastParticipants`: `undefined` \| `null` \| [`IPastParticipants`](../namespaces/proto/interfaces/IPastParticipants.md)[]; `progress`: `undefined` \| `null` \| `number`; `syncType`: `undefined` \| `null` \| [`HistorySyncType`](../namespaces/proto/namespaces/HistorySync/enumerations/HistorySyncType.md); \}\>

Defined in: [src/Utils/history.ts:142](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/history.ts#L142)

## Parameters

### msg

[`IHistorySyncNotification`](../namespaces/proto/namespaces/Message/interfaces/IHistorySyncNotification.md)

### options

`RequestInit`

### logger?

`ILogger`

## Returns

`Promise`\<\{ `chats`: [`Chat`](../type-aliases/Chat.md)[]; `contacts`: [`Contact`](../interfaces/Contact.md)[]; `lidPnMappings`: [`LIDMapping`](../type-aliases/LIDMapping.md)[]; `messages`: [`WAMessage`](../type-aliases/WAMessage.md)[]; `pastParticipants`: `undefined` \| `null` \| [`IPastParticipants`](../namespaces/proto/interfaces/IPastParticipants.md)[]; `progress`: `undefined` \| `null` \| `number`; `syncType`: `undefined` \| `null` \| [`HistorySyncType`](../namespaces/proto/namespaces/HistorySync/enumerations/HistorySyncType.md); \}\>
