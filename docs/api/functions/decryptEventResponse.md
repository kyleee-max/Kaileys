# Function: decryptEventResponse()

> **decryptEventResponse**(`response`, `ctx`): [`EventResponseMessage`](../namespaces/proto/namespaces/Message/classes/EventResponseMessage.md)

Defined in: [src/Utils/process-message.ts:269](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/process-message.ts#L269)

Decrypt an event response

## Parameters

### response

[`IPollEncValue`](../namespaces/proto/namespaces/Message/interfaces/IPollEncValue.md)

encrypted event response

### ctx

`EventContext`

additional info about the event required for decryption

## Returns

[`EventResponseMessage`](../namespaces/proto/namespaces/Message/classes/EventResponseMessage.md)

event response message
