# Variable: NACK\_REASONS

> `const` **NACK\_REASONS**: `object`

Defined in: [src/Utils/decode-wa-message.ts:64](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/decode-wa-message.ts#L64)

NACK reason codes we send to the server (client → server)

## Type declaration

### DBOperationFailed

> **DBOperationFailed**: `number` = `552`

### InvalidHostedCompanionStanza

> **InvalidHostedCompanionStanza**: `number` = `493`

### InvalidProtobuf

> **InvalidProtobuf**: `number` = `491`

### MessageDeletedOnPeer

> **MessageDeletedOnPeer**: `number` = `499`

### MissingMessageSecret

> **MissingMessageSecret**: `number` = `495`

### ParsingError

> **ParsingError**: `number` = `487`

### SenderReachoutTimelocked

> **SenderReachoutTimelocked**: `number` = `463`

### SignalErrorOldCounter

> **SignalErrorOldCounter**: `number` = `496`

### UnhandledError

> **UnhandledError**: `number` = `500`

### UnrecognizedStanza

> **UnrecognizedStanza**: `number` = `488`

### UnrecognizedStanzaClass

> **UnrecognizedStanzaClass**: `number` = `489`

### UnrecognizedStanzaType

> **UnrecognizedStanzaType**: `number` = `490`

### UnsupportedAdminRevoke

> **UnsupportedAdminRevoke**: `number` = `550`

### UnsupportedLIDGroup

> **UnsupportedLIDGroup**: `number` = `551`
