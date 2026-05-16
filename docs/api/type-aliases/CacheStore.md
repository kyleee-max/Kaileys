# Type Alias: CacheStore

> **CacheStore**: `object`

Defined in: [src/Types/Socket.ts:13](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Socket.ts#L13)

## Type declaration

### close()?

> `optional` **close**: () => `void`

#### Returns

`void`

### del()

delete a key from the cache

#### Parameters

##### key

`string`

#### Returns

`number` \| `boolean` \| `void` \| `Promise`\<`void`\>

### flushAll()

flush all data

#### Returns

`void` \| `Promise`\<`void`\>

### get()

get a cached key and change the stats

#### Type Parameters

• **T**

#### Parameters

##### key

`string`

#### Returns

`undefined` \| `T` \| `Promise`\<`T`\>

### set()

set a key in the cache

#### Type Parameters

• **T**

#### Parameters

##### key

`string`

##### value

`T`

#### Returns

`number` \| `boolean` \| `void` \| `Promise`\<`void`\>
