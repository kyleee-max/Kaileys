# Function: buildAckStanza()

> **buildAckStanza**(`node`, `errorCode`?, `meId`?): [`BinaryNode`](../type-aliases/BinaryNode.md)

Defined in: [src/Utils/stanza-ack.ts:11](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/stanza-ack.ts#L11)

Builds an ACK stanza for a received node.
Pure function -- no I/O, no side effects.

Mirrors WhatsApp Web's ACK construction:
- WAWebHandleMsgSendAck.sendAck / sendNack
- WAWebCreateNackFromStanza.createNackFromStanza

## Parameters

### node

[`BinaryNode`](../type-aliases/BinaryNode.md)

### errorCode?

`number`

### meId?

`string`

## Returns

[`BinaryNode`](../type-aliases/BinaryNode.md)
