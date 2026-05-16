# Type Alias: SignalKeyStore

> **SignalKeyStore**: `object`

Defined in: [src/Types/Auth.ts:91](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Auth.ts#L91)

## Type declaration

### clear()?

clear all the data in the store

#### Returns

`Awaitable`\<`void`\>

### get()

#### Type Parameters

• **T** *extends* keyof [`SignalDataTypeMap`](SignalDataTypeMap.md)

#### Parameters

##### type

`T`

##### ids

`string`[]

#### Returns

`Awaitable`\<\{\}\>

### set()

#### Parameters

##### data

[`SignalDataSet`](SignalDataSet.md)

#### Returns

`Awaitable`\<`void`\>
