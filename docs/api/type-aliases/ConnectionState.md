# Type Alias: ConnectionState

> **ConnectionState**: `object`

Defined in: [src/Types/State.ts:17](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/State.ts#L17)

## Type declaration

### connection

> **connection**: [`WAConnectionState`](WAConnectionState.md)

connection is now open, connecting or closed

### isNewLogin?

> `optional` **isNewLogin**: `boolean`

is this a new login

### isOnline?

> `optional` **isOnline**: `boolean`

if the client is shown as an active, online client.
If this is false, the primary phone and other devices will receive notifs

### lastDisconnect?

> `optional` **lastDisconnect**: `object`

the error that caused the connection to close

#### lastDisconnect.date

> **date**: `Date`

#### lastDisconnect.error

> **error**: `Boom` \| `Error` \| `undefined`

### legacy?

> `optional` **legacy**: `object`

legacy connection options

#### legacy.phoneConnected

> **phoneConnected**: `boolean`

#### legacy.user?

> `optional` **user**: [`Contact`](../interfaces/Contact.md)

### qr?

> `optional` **qr**: `string`

the current QR code

### reachoutTimeLock?

> `optional` **reachoutTimeLock**: [`ReachoutTimelockState`](ReachoutTimelockState.md)

When you are in this state, WhatsApp prevents outgoing messages and calls.

### receivedPendingNotifications?

> `optional` **receivedPendingNotifications**: `boolean`

has the device received all pending notifications while it was offline
