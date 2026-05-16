# Type Alias: MessageContentGenerationOptions

> **MessageContentGenerationOptions**: [`MediaGenerationOptions`](MediaGenerationOptions.md) & `object`

Defined in: [src/Types/Message.ts:369](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Message.ts#L369)

## Type declaration

### getCallLink()?

> `optional` **getCallLink**: (`type`, `event`?) => `Promise`\<`string` \| `undefined`\>

#### Parameters

##### type

`"audio"` | `"video"`

##### event?

###### startTime

`number`

#### Returns

`Promise`\<`string` \| `undefined`\>

### getProfilePicUrl()?

> `optional` **getProfilePicUrl**: (`jid`, `type`) => `Promise`\<`string` \| `undefined`\>

#### Parameters

##### jid

`string`

##### type

`"image"` | `"preview"`

#### Returns

`Promise`\<`string` \| `undefined`\>

### getUrlInfo()?

> `optional` **getUrlInfo**: (`text`) => `Promise`\<[`WAUrlInfo`](../interfaces/WAUrlInfo.md) \| `undefined`\>

#### Parameters

##### text

`string`

#### Returns

`Promise`\<[`WAUrlInfo`](../interfaces/WAUrlInfo.md) \| `undefined`\>

### jid?

> `optional` **jid**: `string`
