# Type Alias: SignalDataTypeMap

> **SignalDataTypeMap**: `object`

Defined in: [src/Types/Auth.ts:74](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Auth.ts#L74)

## Type declaration

### app-state-sync-key

> **app-state-sync-key**: [`IAppStateSyncKeyData`](../namespaces/proto/namespaces/Message/interfaces/IAppStateSyncKeyData.md)

### app-state-sync-version

> **app-state-sync-version**: [`LTHashState`](LTHashState.md)

### device-list

> **device-list**: `string`[]

### identity-key

> **identity-key**: `Uint8Array`

### lid-mapping

> **lid-mapping**: `string`

### pre-key

> **pre-key**: [`KeyPair`](KeyPair.md)

### sender-key

> **sender-key**: `Uint8Array`

### sender-key-memory

> **sender-key-memory**: `object`

#### Index Signature

\[`jid`: `string`\]: `boolean`

### session

> **session**: `Uint8Array`

### tctoken

> **tctoken**: `object`

#### tctoken.senderTimestamp?

> `optional` **senderTimestamp**: `number`

#### tctoken.timestamp?

> `optional` **timestamp**: `string`

#### tctoken.token

> **token**: `Buffer`
