# Function: isAppStateSyncIrrecoverable()

> **isAppStateSyncIrrecoverable**(`error`, `attempts`): `boolean`

Defined in: [src/Utils/chat-utils.ts:159](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L159)

Determines if an app state sync error is unrecoverable.
TypeError indicates a WASM crash; otherwise we give up after MAX_SYNC_ATTEMPTS.
Missing keys are NOT checked here — they are handled separately as "Blocked".

## Parameters

### error

`any`

### attempts

`number`

## Returns

`boolean`
