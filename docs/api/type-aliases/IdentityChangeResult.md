# Type Alias: IdentityChangeResult

> **IdentityChangeResult**: \{ `action`: `"no_identity_node"`; \} \| \{ `action`: `"invalid_notification"`; \} \| \{ `action`: `"skipped_companion_device"`; `device`: `number`; \} \| \{ `action`: `"skipped_self_primary"`; \} \| \{ `action`: `"debounced"`; \} \| \{ `action`: `"skipped_offline"`; \} \| \{ `action`: `"skipped_no_session"`; \} \| \{ `action`: `"session_refreshed"`; \} \| \{ `action`: `"session_refresh_failed"`; `error`: `unknown`; \}

Defined in: [src/Utils/identity-change-handler.ts:6](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/identity-change-handler.ts#L6)
