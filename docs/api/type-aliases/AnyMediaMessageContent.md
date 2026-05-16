# Type Alias: AnyMediaMessageContent

> **AnyMediaMessageContent**: `object` & `Mentionable` & `Contextable` & `WithDimensions` \| `object` & `Mentionable` & `Contextable` & `WithDimensions` \| \{ `audio`: [`WAMediaUpload`](WAMediaUpload.md); `ptt`: `boolean`; `seconds`: `number`; \} \| `object` & `WithDimensions` \| `object` & `Contextable` & `object` & `Editable` & `object`

Defined in: [src/Types/Message.ts:174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Message.ts#L174)

## Type declaration

### mimetype?

> `optional` **mimetype**: `string`

## Type declaration

### albumParentKey?

> `optional` **albumParentKey**: [`WAMessageKey`](WAMessageKey.md)

key of the parent albumMessage to associate this media with
