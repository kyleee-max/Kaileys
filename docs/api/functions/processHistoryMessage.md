# Function: processHistoryMessage()

> **processHistoryMessage**(`item`, `logger`?): `object`

Defined in: [src/Utils/history.ts:47](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/history.ts#L47)

## Parameters

### item

[`IHistorySync`](../namespaces/proto/interfaces/IHistorySync.md)

### logger?

`ILogger`

## Returns

`object`

### chats

> **chats**: [`Chat`](../type-aliases/Chat.md)[]

### contacts

> **contacts**: [`Contact`](../interfaces/Contact.md)[]

### lidPnMappings

> **lidPnMappings**: [`LIDMapping`](../type-aliases/LIDMapping.md)[]

### messages

> **messages**: [`WAMessage`](../type-aliases/WAMessage.md)[]

### pastParticipants

> **pastParticipants**: `undefined` \| `null` \| [`IPastParticipants`](../namespaces/proto/interfaces/IPastParticipants.md)[] = `item.pastParticipants`

### progress

> **progress**: `undefined` \| `null` \| `number` = `item.progress`

### syncType

> **syncType**: `undefined` \| `null` \| [`HistorySyncType`](../namespaces/proto/namespaces/HistorySync/enumerations/HistorySyncType.md) = `item.syncType`
