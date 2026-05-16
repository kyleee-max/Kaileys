# Type Alias: AuthenticationCreds

> **AuthenticationCreds**: [`SignalCreds`](SignalCreds.md) & `object`

Defined in: [src/Types/Auth.ts:48](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Auth.ts#L48)

## Type declaration

### account?

> `optional` **account**: [`IADVSignedDeviceIdentity`](../namespaces/proto/interfaces/IADVSignedDeviceIdentity.md)

### accountSettings

> **accountSettings**: [`AccountSettings`](AccountSettings.md)

### accountSyncCounter

> **accountSyncCounter**: `number`

number of times history & app state has been synced

### additionalData?

> `optional` **additionalData**: `any`

### advSecretKey

> **advSecretKey**: `string`

### firstUnuploadedPreKeyId

> **firstUnuploadedPreKeyId**: `number`

### lastAccountSyncTimestamp?

> `optional` **lastAccountSyncTimestamp**: `number`

### lastPropHash

> **lastPropHash**: `string` \| `undefined`

### me?

> `optional` **me**: [`Contact`](../interfaces/Contact.md)

### myAppStateKeyId?

> `optional` **myAppStateKeyId**: `string`

### nextPreKeyId

> **nextPreKeyId**: `number`

### noiseKey

> `readonly` **noiseKey**: [`KeyPair`](KeyPair.md)

### pairingCode

> **pairingCode**: `string` \| `undefined`

### pairingEphemeralKeyPair

> `readonly` **pairingEphemeralKeyPair**: [`KeyPair`](KeyPair.md)

### platform?

> `optional` **platform**: `string`

### processedHistoryMessages

> **processedHistoryMessages**: [`MinimalMessage`](MinimalMessage.md)[]

### registered

> **registered**: `boolean`

### routingInfo

> **routingInfo**: `Buffer` \| `undefined`

### signalIdentities?

> `optional` **signalIdentities**: [`SignalIdentity`](SignalIdentity.md)[]
