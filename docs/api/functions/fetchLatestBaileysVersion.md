# Function: fetchLatestBaileysVersion()

> **fetchLatestBaileysVersion**(`options`): `Promise`\<\{ `error`: `undefined`; `isLatest`: `boolean`; `version`: [`WAVersion`](../type-aliases/WAVersion.md); \} \| \{ `error`: `unknown`; `isLatest`: `boolean`; `version`: [`WAVersion`](../type-aliases/WAVersion.md); \}\>

Defined in: [src/Utils/generics.ts:238](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/generics.ts#L238)

utility that fetches latest baileys version from the master branch.
Use to ensure your WA connection is always on the latest version

## Parameters

### options

`RequestInit` = `{}`

## Returns

`Promise`\<\{ `error`: `undefined`; `isLatest`: `boolean`; `version`: [`WAVersion`](../type-aliases/WAVersion.md); \} \| \{ `error`: `unknown`; `isLatest`: `boolean`; `version`: [`WAVersion`](../type-aliases/WAVersion.md); \}\>
