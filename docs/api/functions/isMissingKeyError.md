# Function: isMissingKeyError()

> **isMissingKeyError**(`error`): `boolean`

Defined in: [src/Utils/chat-utils.ts:150](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/chat-utils.ts#L150)

Check if an error is a missing app state sync key.
WA Web treats these as "Blocked" (waits for key arrival), not fatal.
In Baileys we retry with a snapshot which may use a different key.

## Parameters

### error

`any`

## Returns

`boolean`
