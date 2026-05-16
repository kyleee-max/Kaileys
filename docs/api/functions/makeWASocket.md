# Function: makeWASocket()

> **makeWASocket**(`config`): `object`

Defined in: [src/Socket/index.ts:6](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Socket/index.ts#L6)

## Parameters

### config

[`UserFacingSocketConfig`](../type-aliases/UserFacingSocketConfig.md)

## Returns

`object`

### addChatLabel()

> **addChatLabel**: (`jid`, `labelId`) => `Promise`\<`void`\>

Adds label for the chats

#### Parameters

##### jid

`string`

##### labelId

`string`

#### Returns

`Promise`\<`void`\>

### addLabel()

> **addLabel**: (`jid`, `labels`) => `Promise`\<`void`\>

Adds label

#### Parameters

##### jid

`string`

##### labels

`LabelActionBody`

#### Returns

`Promise`\<`void`\>

### addMessageLabel()

> **addMessageLabel**: (`jid`, `messageId`, `labelId`) => `Promise`\<`void`\>

Adds label for the message

#### Parameters

##### jid

`string`

##### messageId

`string`

##### labelId

`string`

#### Returns

`Promise`\<`void`\>

### addOrEditContact()

> **addOrEditContact**: (`jid`, `contact`) => `Promise`\<`void`\>

Add or Edit Contact

#### Parameters

##### jid

`string`

##### contact

[`IContactAction`](../namespaces/proto/namespaces/SyncActionValue/interfaces/IContactAction.md)

#### Returns

`Promise`\<`void`\>

### addOrEditQuickReply()

> **addOrEditQuickReply**: (`quickReply`) => `Promise`\<`void`\>

Add or Edit Quick Reply

#### Parameters

##### quickReply

`QuickReplyAction`

#### Returns

`Promise`\<`void`\>

### appPatch()

> **appPatch**: (`patchCreate`) => `Promise`\<`void`\>

#### Parameters

##### patchCreate

[`WAPatchCreate`](../type-aliases/WAPatchCreate.md)

#### Returns

`Promise`\<`void`\>

### appStatePatchMutex

> **appStatePatchMutex**: `object`

#### appStatePatchMutex.mutex()

##### Type Parameters

• **T**

##### Parameters

###### code

() => `T` \| `Promise`\<`T`\>

##### Returns

`Promise`\<`T`\>

### assertSessions()

> **assertSessions**: (`jids`, `force`?) => `Promise`\<`boolean`\>

#### Parameters

##### jids

`string`[]

##### force?

`boolean`

#### Returns

`Promise`\<`boolean`\>

### authState

> **authState**: `object`

#### authState.creds

> **creds**: [`AuthenticationCreds`](../type-aliases/AuthenticationCreds.md)

#### authState.keys

> **keys**: [`SignalKeyStoreWithTransaction`](../type-aliases/SignalKeyStoreWithTransaction.md)

### chatModify()

> **chatModify**: (`mod`, `jid`) => `Promise`\<`void`\>

modify a chat -- mark unread, read etc.
lastMessages must be sorted in reverse chronologically
requires the last messages till the last message received; required for archive & unread

#### Parameters

##### mod

[`ChatModification`](../type-aliases/ChatModification.md)

##### jid

`string`

#### Returns

`Promise`\<`void`\>

### cleanDirtyBits()

> **cleanDirtyBits**: (`type`, `fromTimestamp`?) => `Promise`\<`void`\>

#### Parameters

##### type

`"account_sync"` | `"groups"`

##### fromTimestamp?

`string` | `number`

#### Returns

`Promise`\<`void`\>

### communityAcceptInvite()

> **communityAcceptInvite**: (`code`) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### code

`string`

#### Returns

`Promise`\<`undefined` \| `string`\>

### communityAcceptInviteV4()

> **communityAcceptInviteV4**: (...`args`) => `Promise`\<`any`\>

accept a CommunityInviteMessage

#### Parameters

##### args

...\[`string` \| [`WAMessageKey`](../type-aliases/WAMessageKey.md), [`IGroupInviteMessage`](../namespaces/proto/namespaces/Message/interfaces/IGroupInviteMessage.md)\]

#### Returns

`Promise`\<`any`\>

### communityCreate()

> **communityCreate**: (`subject`, `body`) => `Promise`\<`null` \| [`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### subject

`string`

##### body

`string`

#### Returns

`Promise`\<`null` \| [`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### communityCreateGroup()

> **communityCreateGroup**: (`subject`, `participants`, `parentCommunityJid`) => `Promise`\<`null` \| [`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### subject

`string`

##### participants

`string`[]

##### parentCommunityJid

`string`

#### Returns

`Promise`\<`null` \| [`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### communityFetchAllParticipating()

> **communityFetchAllParticipating**: () => `Promise`\<\{\}\>

#### Returns

`Promise`\<\{\}\>

### communityFetchLinkedGroups()

> **communityFetchLinkedGroups**: (`jid`) => `Promise`\<\{ `communityJid`: `string`; `isCommunity`: `boolean`; `linkedGroups`: `object`[]; \}\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<\{ `communityJid`: `string`; `isCommunity`: `boolean`; `linkedGroups`: `object`[]; \}\>

### communityGetInviteInfo()

> **communityGetInviteInfo**: (`code`) => `Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### code

`string`

#### Returns

`Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### communityInviteCode()

> **communityInviteCode**: (`jid`) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`undefined` \| `string`\>

### communityJoinApprovalMode()

> **communityJoinApprovalMode**: (`jid`, `mode`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### mode

`"on"` | `"off"`

#### Returns

`Promise`\<`void`\>

### communityLeave()

> **communityLeave**: (`id`) => `Promise`\<`void`\>

#### Parameters

##### id

`string`

#### Returns

`Promise`\<`void`\>

### communityLinkGroup()

> **communityLinkGroup**: (`groupJid`, `parentCommunityJid`) => `Promise`\<`void`\>

#### Parameters

##### groupJid

`string`

##### parentCommunityJid

`string`

#### Returns

`Promise`\<`void`\>

### communityMemberAddMode()

> **communityMemberAddMode**: (`jid`, `mode`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### mode

`"all_member_add"` | `"admin_add"`

#### Returns

`Promise`\<`void`\>

### communityMetadata()

> **communityMetadata**: (`jid`) => `Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### communityParticipantsUpdate()

> **communityParticipantsUpdate**: (`jid`, `participants`, `action`) => `Promise`\<`object`[]\>

#### Parameters

##### jid

`string`

##### participants

`string`[]

##### action

[`ParticipantAction`](../type-aliases/ParticipantAction.md)

#### Returns

`Promise`\<`object`[]\>

### communityRequestParticipantsList()

> **communityRequestParticipantsList**: (`jid`) => `Promise`\<`object`[]\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`object`[]\>

### communityRequestParticipantsUpdate()

> **communityRequestParticipantsUpdate**: (`jid`, `participants`, `action`) => `Promise`\<`object`[]\>

#### Parameters

##### jid

`string`

##### participants

`string`[]

##### action

`"reject"` | `"approve"`

#### Returns

`Promise`\<`object`[]\>

### communityRevokeInvite()

> **communityRevokeInvite**: (`jid`) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`undefined` \| `string`\>

### communityRevokeInviteV4()

> **communityRevokeInviteV4**: (`communityJid`, `invitedJid`) => `Promise`\<`boolean`\>

revoke a v4 invite for someone

#### Parameters

##### communityJid

`string`

community jid

##### invitedJid

`string`

jid of person you invited

#### Returns

`Promise`\<`boolean`\>

true if successful

### communitySettingUpdate()

> **communitySettingUpdate**: (`jid`, `setting`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### setting

`"announcement"` | `"locked"` | `"not_announcement"` | `"unlocked"`

#### Returns

`Promise`\<`void`\>

### communityToggleEphemeral()

> **communityToggleEphemeral**: (`jid`, `ephemeralExpiration`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### ephemeralExpiration

`number`

#### Returns

`Promise`\<`void`\>

### communityUnlinkGroup()

> **communityUnlinkGroup**: (`groupJid`, `parentCommunityJid`) => `Promise`\<`void`\>

#### Parameters

##### groupJid

`string`

##### parentCommunityJid

`string`

#### Returns

`Promise`\<`void`\>

### communityUpdateDescription()

> **communityUpdateDescription**: (`jid`, `description`?) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### description?

`string`

#### Returns

`Promise`\<`void`\>

### communityUpdateSubject()

> **communityUpdateSubject**: (`jid`, `subject`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### subject

`string`

#### Returns

`Promise`\<`void`\>

### createCallLink()

> **createCallLink**: (`type`, `event`?, `timeoutMs`?) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### type

`"video"` | `"audio"`

##### event?

###### startTime

`number`

##### timeoutMs?

`number`

#### Returns

`Promise`\<`undefined` \| `string`\>

### createParticipantNodes()

> **createParticipantNodes**: (`recipientJids`, `message`, `extraAttrs`?, `dsmMessage`?) => `Promise`\<\{ `nodes`: [`BinaryNode`](../type-aliases/BinaryNode.md)[]; `shouldIncludeDeviceIdentity`: `boolean`; \}\>

#### Parameters

##### recipientJids

`string`[]

##### message

[`IMessage`](../namespaces/proto/interfaces/IMessage.md)

##### extraAttrs?

##### dsmMessage?

[`IMessage`](../namespaces/proto/interfaces/IMessage.md)

#### Returns

`Promise`\<\{ `nodes`: [`BinaryNode`](../type-aliases/BinaryNode.md)[]; `shouldIncludeDeviceIdentity`: `boolean`; \}\>

### devicesMutex

> **devicesMutex**: `object`

#### devicesMutex.mutex()

##### Type Parameters

• **T**

##### Parameters

###### code

() => `T` \| `Promise`\<`T`\>

##### Returns

`Promise`\<`T`\>

### digestKeyBundle()

> **digestKeyBundle**: () => `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

### end()

> **end**: (`error`) => `Promise`\<`void`\>

#### Parameters

##### error

`undefined` | `Error`

#### Returns

`Promise`\<`void`\>

### ev

> **ev**: `BaileysBufferableEventEmitter`

### executeUSyncQuery()

> **executeUSyncQuery**: (`usyncQuery`) => `Promise`\<`undefined` \| [`USyncQueryResult`](../type-aliases/USyncQueryResult.md)\>

#### Parameters

##### usyncQuery

[`USyncQuery`](../classes/USyncQuery.md)

#### Returns

`Promise`\<`undefined` \| [`USyncQueryResult`](../type-aliases/USyncQueryResult.md)\>

### fetchAccountReachoutTimelock()

> **fetchAccountReachoutTimelock**: () => `Promise`\<[`ReachoutTimelockState`](../type-aliases/ReachoutTimelockState.md)\>

Fetches your account's standing when it comes to restrictions.

#### Returns

`Promise`\<[`ReachoutTimelockState`](../type-aliases/ReachoutTimelockState.md)\>

Returns the state of the restrictions.

### fetchBlocklist()

> **fetchBlocklist**: () => `Promise`\<(`undefined` \| `string`)[]\>

#### Returns

`Promise`\<(`undefined` \| `string`)[]\>

### fetchDisappearingDuration()

> **fetchDisappearingDuration**: (...`jids`) => `Promise`\<`undefined` \| [`USyncQueryResultList`](../type-aliases/USyncQueryResultList.md)[]\>

#### Parameters

##### jids

...`string`[]

#### Returns

`Promise`\<`undefined` \| [`USyncQueryResultList`](../type-aliases/USyncQueryResultList.md)[]\>

### fetchMessageHistory()

> **fetchMessageHistory**: (`count`, `oldestMsgKey`, `oldestMsgTimestamp`) => `Promise`\<`string`\>

#### Parameters

##### count

`number`

##### oldestMsgKey

[`WAMessageKey`](../type-aliases/WAMessageKey.md)

##### oldestMsgTimestamp

`number` | `Long`

#### Returns

`Promise`\<`string`\>

### fetchNewChatMessageCap()

> **fetchNewChatMessageCap**: () => `Promise`\<[`NewChatMessageCapInfo`](../type-aliases/NewChatMessageCapInfo.md)\>

Fetches your account's new chat limits.

#### Returns

`Promise`\<[`NewChatMessageCapInfo`](../type-aliases/NewChatMessageCapInfo.md)\>

Returns the quota and the usage.

### fetchPrivacySettings()

> **fetchPrivacySettings**: (`force`) => `Promise`\<\{\}\>

#### Parameters

##### force

`boolean` = `false`

#### Returns

`Promise`\<\{\}\>

### fetchStatus()

> **fetchStatus**: (...`jids`) => `Promise`\<`undefined` \| [`USyncQueryResultList`](../type-aliases/USyncQueryResultList.md)[]\>

#### Parameters

##### jids

...`string`[]

#### Returns

`Promise`\<`undefined` \| [`USyncQueryResultList`](../type-aliases/USyncQueryResultList.md)[]\>

### generateMessageTag()

> **generateMessageTag**: () => `string`

#### Returns

`string`

### getBotListV2()

> **getBotListV2**: () => `Promise`\<[`BotListInfo`](../type-aliases/BotListInfo.md)[]\>

#### Returns

`Promise`\<[`BotListInfo`](../type-aliases/BotListInfo.md)[]\>

### getBusinessProfile()

> **getBusinessProfile**: (`jid`) => `Promise`\<`void` \| [`WABusinessProfile`](../type-aliases/WABusinessProfile.md)\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`void` \| [`WABusinessProfile`](../type-aliases/WABusinessProfile.md)\>

### getCatalog()

> **getCatalog**: (`__namedParameters`) => `Promise`\<\{ `nextPageCursor`: `undefined` \| `string`; `products`: [`Product`](../type-aliases/Product.md)[]; \}\>

#### Parameters

##### \_\_namedParameters

[`GetCatalogOptions`](../type-aliases/GetCatalogOptions.md)

#### Returns

`Promise`\<\{ `nextPageCursor`: `undefined` \| `string`; `products`: [`Product`](../type-aliases/Product.md)[]; \}\>

### getCollections()

> **getCollections**: (`jid`?, `limit`) => `Promise`\<\{ `collections`: [`CatalogCollection`](../type-aliases/CatalogCollection.md)[]; \}\>

#### Parameters

##### jid?

`string`

##### limit?

`number` = `51`

#### Returns

`Promise`\<\{ `collections`: [`CatalogCollection`](../type-aliases/CatalogCollection.md)[]; \}\>

### getMediaHost()

> **getMediaHost**: () => `string`

#### Returns

`string`

### getOrderDetails()

> **getOrderDetails**: (`orderId`, `tokenBase64`) => `Promise`\<[`OrderDetails`](../type-aliases/OrderDetails.md)\>

#### Parameters

##### orderId

`string`

##### tokenBase64

`string`

#### Returns

`Promise`\<[`OrderDetails`](../type-aliases/OrderDetails.md)\>

### getUSyncDevices()

> **getUSyncDevices**: (`jids`, `useCache`, `ignoreZeroDevices`) => `Promise`\<`DeviceWithJid`[]\>

Fetch all the devices we've to send a message to

#### Parameters

##### jids

`string`[]

##### useCache

`boolean`

##### ignoreZeroDevices

`boolean`

#### Returns

`Promise`\<`DeviceWithJid`[]\>

### groupAcceptInvite()

> **groupAcceptInvite**: (`code`) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### code

`string`

#### Returns

`Promise`\<`undefined` \| `string`\>

### groupAcceptInviteV4()

> **groupAcceptInviteV4**: (...`args`) => `Promise`\<`any`\>

accept a GroupInviteMessage

#### Parameters

##### args

...\[`string` \| [`WAMessageKey`](../type-aliases/WAMessageKey.md), [`IGroupInviteMessage`](../namespaces/proto/namespaces/Message/interfaces/IGroupInviteMessage.md)\]

#### Returns

`Promise`\<`any`\>

### groupCreate()

> **groupCreate**: (`subject`, `participants`) => `Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### subject

`string`

##### participants

`string`[]

#### Returns

`Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### groupFetchAllParticipating()

> **groupFetchAllParticipating**: () => `Promise`\<\{\}\>

#### Returns

`Promise`\<\{\}\>

### groupGetInviteInfo()

> **groupGetInviteInfo**: (`code`) => `Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### code

`string`

#### Returns

`Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### groupInviteCode()

> **groupInviteCode**: (`jid`) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`undefined` \| `string`\>

### groupJoinApprovalMode()

> **groupJoinApprovalMode**: (`jid`, `mode`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### mode

`"on"` | `"off"`

#### Returns

`Promise`\<`void`\>

### groupLeave()

> **groupLeave**: (`id`) => `Promise`\<`void`\>

#### Parameters

##### id

`string`

#### Returns

`Promise`\<`void`\>

### groupMemberAddMode()

> **groupMemberAddMode**: (`jid`, `mode`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### mode

`"all_member_add"` | `"admin_add"`

#### Returns

`Promise`\<`void`\>

### groupMetadata()

> **groupMetadata**: (`jid`) => `Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<[`GroupMetadata`](../interfaces/GroupMetadata.md)\>

### groupParticipantsUpdate()

> **groupParticipantsUpdate**: (`jid`, `participants`, `action`) => `Promise`\<`object`[]\>

#### Parameters

##### jid

`string`

##### participants

`string`[]

##### action

[`ParticipantAction`](../type-aliases/ParticipantAction.md)

#### Returns

`Promise`\<`object`[]\>

### groupRequestParticipantsList()

> **groupRequestParticipantsList**: (`jid`) => `Promise`\<`object`[]\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`object`[]\>

### groupRequestParticipantsUpdate()

> **groupRequestParticipantsUpdate**: (`jid`, `participants`, `action`) => `Promise`\<`object`[]\>

#### Parameters

##### jid

`string`

##### participants

`string`[]

##### action

`"reject"` | `"approve"`

#### Returns

`Promise`\<`object`[]\>

### groupRevokeInvite()

> **groupRevokeInvite**: (`jid`) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`undefined` \| `string`\>

### groupRevokeInviteV4()

> **groupRevokeInviteV4**: (`groupJid`, `invitedJid`) => `Promise`\<`boolean`\>

revoke a v4 invite for someone

#### Parameters

##### groupJid

`string`

group jid

##### invitedJid

`string`

jid of person you invited

#### Returns

`Promise`\<`boolean`\>

true if successful

### groupSettingUpdate()

> **groupSettingUpdate**: (`jid`, `setting`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### setting

`"announcement"` | `"locked"` | `"not_announcement"` | `"unlocked"`

#### Returns

`Promise`\<`void`\>

### groupToggleEphemeral()

> **groupToggleEphemeral**: (`jid`, `ephemeralExpiration`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### ephemeralExpiration

`number`

#### Returns

`Promise`\<`void`\>

### groupUpdateDescription()

> **groupUpdateDescription**: (`jid`, `description`?) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### description?

`string`

#### Returns

`Promise`\<`void`\>

### groupUpdateSubject()

> **groupUpdateSubject**: (`jid`, `subject`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### subject

`string`

#### Returns

`Promise`\<`void`\>

### issuePrivacyTokens()

> **issuePrivacyTokens**: (`jids`, `timestamp`?) => `Promise`\<`any`\>

#### Parameters

##### jids

`string`[]

##### timestamp?

`number`

#### Returns

`Promise`\<`any`\>

### logger

> **logger**: `ILogger` = `config.logger`

### logout()

> **logout**: (`msg`?) => `Promise`\<`void`\>

logout & invalidate connection

#### Parameters

##### msg?

`string`

#### Returns

`Promise`\<`void`\>

### messageMutex

> **messageMutex**: `object`

#### messageMutex.mutex()

##### Type Parameters

• **T**

##### Parameters

###### code

() => `T` \| `Promise`\<`T`\>

##### Returns

`Promise`\<`T`\>

### messageRetryManager

> **messageRetryManager**: `null` \| [`MessageRetryManager`](../classes/MessageRetryManager.md)

### newsletterAdminCount()

> **newsletterAdminCount**: (`jid`) => `Promise`\<`number`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`number`\>

### newsletterChangeOwner()

> **newsletterChangeOwner**: (`jid`, `newOwnerJid`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### newOwnerJid

`string`

#### Returns

`Promise`\<`void`\>

### newsletterCreate()

> **newsletterCreate**: (`name`, `description`?) => `Promise`\<[`NewsletterMetadata`](../interfaces/NewsletterMetadata.md)\>

#### Parameters

##### name

`string`

##### description?

`string`

#### Returns

`Promise`\<[`NewsletterMetadata`](../interfaces/NewsletterMetadata.md)\>

### newsletterDelete()

> **newsletterDelete**: (`jid`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`void`\>

### newsletterDemote()

> **newsletterDemote**: (`jid`, `userJid`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### userJid

`string`

#### Returns

`Promise`\<`void`\>

### newsletterFetchMessages()

> **newsletterFetchMessages**: (`jid`, `count`, `since`, `after`) => `Promise`\<`any`\>

#### Parameters

##### jid

`string`

##### count

`number`

##### since

`number`

##### after

`number`

#### Returns

`Promise`\<`any`\>

### newsletterFollow()

> **newsletterFollow**: (`jid`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterMetadata()

> **newsletterMetadata**: (`type`, `key`) => `Promise`\<`null` \| [`NewsletterMetadata`](../interfaces/NewsletterMetadata.md)\>

#### Parameters

##### type

`"invite"` | `"jid"`

##### key

`string`

#### Returns

`Promise`\<`null` \| [`NewsletterMetadata`](../interfaces/NewsletterMetadata.md)\>

### newsletterMute()

> **newsletterMute**: (`jid`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterReactMessage()

> **newsletterReactMessage**: (`jid`, `serverId`, `reaction`?) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### serverId

`string`

##### reaction?

`string`

#### Returns

`Promise`\<`void`\>

### newsletterRemovePicture()

> **newsletterRemovePicture**: (`jid`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterSubscribers()

> **newsletterSubscribers**: (`jid`) => `Promise`\<\{ `subscribers`: `number`; \}\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<\{ `subscribers`: `number`; \}\>

### newsletterUnfollow()

> **newsletterUnfollow**: (`jid`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterUnmute()

> **newsletterUnmute**: (`jid`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterUpdate()

> **newsletterUpdate**: (`jid`, `updates`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

##### updates

[`NewsletterUpdate`](../type-aliases/NewsletterUpdate.md)

#### Returns

`Promise`\<`unknown`\>

### newsletterUpdateDescription()

> **newsletterUpdateDescription**: (`jid`, `description`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

##### description

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterUpdateName()

> **newsletterUpdateName**: (`jid`, `name`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

##### name

`string`

#### Returns

`Promise`\<`unknown`\>

### newsletterUpdatePicture()

> **newsletterUpdatePicture**: (`jid`, `content`) => `Promise`\<`unknown`\>

#### Parameters

##### jid

`string`

##### content

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

#### Returns

`Promise`\<`unknown`\>

### notificationMutex

> **notificationMutex**: `object`

#### notificationMutex.mutex()

##### Type Parameters

• **T**

##### Parameters

###### code

() => `T` \| `Promise`\<`T`\>

##### Returns

`Promise`\<`T`\>

### onUnexpectedError()

> **onUnexpectedError**: (`err`, `msg`) => `void`

log & process any unexpected errors

#### Parameters

##### err

`Error` | `Boom`\<`any`\>

##### msg

`string`

#### Returns

`void`

### onWhatsApp()

> **onWhatsApp**: (...`phoneNumber`) => `Promise`\<`undefined` \| `object`[]\>

#### Parameters

##### phoneNumber

...`string`[]

#### Returns

`Promise`\<`undefined` \| `object`[]\>

### placeholderResendCache

> **placeholderResendCache**: [`CacheStore`](../type-aliases/CacheStore.md)

### presenceSubscribe()

> **presenceSubscribe**: (`toJid`) => `Promise`\<`void`\>

#### Parameters

##### toJid

`string`

the jid to subscribe to

#### Returns

`Promise`\<`void`\>

### productCreate()

> **productCreate**: (`create`) => `Promise`\<[`Product`](../type-aliases/Product.md)\>

#### Parameters

##### create

[`ProductCreate`](../type-aliases/ProductCreate.md)

#### Returns

`Promise`\<[`Product`](../type-aliases/Product.md)\>

### productDelete()

> **productDelete**: (`productIds`) => `Promise`\<\{ `deleted`: `number`; \}\>

#### Parameters

##### productIds

`string`[]

#### Returns

`Promise`\<\{ `deleted`: `number`; \}\>

### productUpdate()

> **productUpdate**: (`productId`, `update`) => `Promise`\<[`Product`](../type-aliases/Product.md)\>

#### Parameters

##### productId

`string`

##### update

[`ProductUpdate`](../type-aliases/ProductUpdate.md)

#### Returns

`Promise`\<[`Product`](../type-aliases/Product.md)\>

### profilePictureUrl()

> **profilePictureUrl**: (`jid`, `type`, `timeoutMs`?) => `Promise`\<`undefined` \| `string`\>

fetch the profile picture of a user/group
type = "preview" for a low res picture
type = "image for the high res picture"

#### Parameters

##### jid

`string`

##### type

`"image"` | `"preview"`

##### timeoutMs?

`number`

#### Returns

`Promise`\<`undefined` \| `string`\>

### query()

> **query**: (`node`, `timeoutMs`?) => `Promise`\<`any`\>

send a query, and wait for its response. auto-generates message ID if not provided

#### Parameters

##### node

[`BinaryNode`](../type-aliases/BinaryNode.md)

##### timeoutMs?

`number`

#### Returns

`Promise`\<`any`\>

### readMessages()

> **readMessages**: (`keys`) => `Promise`\<`void`\>

Bulk read messages. Keys can be from different chats & participants

#### Parameters

##### keys

[`WAMessageKey`](../type-aliases/WAMessageKey.md)[]

#### Returns

`Promise`\<`void`\>

### receiptMutex

> **receiptMutex**: `object`

#### receiptMutex.mutex()

##### Type Parameters

• **T**

##### Parameters

###### code

() => `T` \| `Promise`\<`T`\>

##### Returns

`Promise`\<`T`\>

### refreshMediaConn()

> **refreshMediaConn**: (`forceGet`) => `Promise`\<[`MediaConnInfo`](../type-aliases/MediaConnInfo.md)\>

#### Parameters

##### forceGet

`boolean` = `false`

#### Returns

`Promise`\<[`MediaConnInfo`](../type-aliases/MediaConnInfo.md)\>

### registerSocketEndHandler()

> **registerSocketEndHandler**: (`handler`) => `void`

#### Parameters

##### handler

(`error`) => `void` \| `Promise`\<`void`\>

#### Returns

`void`

### rejectCall()

> **rejectCall**: (`callId`, `callFrom`) => `Promise`\<`void`\>

#### Parameters

##### callId

`string`

##### callFrom

`string`

#### Returns

`Promise`\<`void`\>

### relayMessage()

> **relayMessage**: (`jid`, `message`, `__namedParameters`) => `Promise`\<`string`\>

#### Parameters

##### jid

`string`

##### message

[`IMessage`](../namespaces/proto/interfaces/IMessage.md)

##### \_\_namedParameters

[`MessageRelayOptions`](../type-aliases/MessageRelayOptions.md)

#### Returns

`Promise`\<`string`\>

### removeChatLabel()

> **removeChatLabel**: (`jid`, `labelId`) => `Promise`\<`void`\>

Removes label for the chat

#### Parameters

##### jid

`string`

##### labelId

`string`

#### Returns

`Promise`\<`void`\>

### removeContact()

> **removeContact**: (`jid`) => `Promise`\<`void`\>

Remove Contact

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`void`\>

### removeCoverPhoto()

> **removeCoverPhoto**: (`id`) => `Promise`\<`any`\>

#### Parameters

##### id

`string`

#### Returns

`Promise`\<`any`\>

### removeMessageLabel()

> **removeMessageLabel**: (`jid`, `messageId`, `labelId`) => `Promise`\<`void`\>

Removes label for the message

#### Parameters

##### jid

`string`

##### messageId

`string`

##### labelId

`string`

#### Returns

`Promise`\<`void`\>

### removeProfilePicture()

> **removeProfilePicture**: (`jid`) => `Promise`\<`void`\>

remove the profile picture for yourself or a group

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`void`\>

### removeQuickReply()

> **removeQuickReply**: (`timestamp`) => `Promise`\<`void`\>

Remove Quick Reply

#### Parameters

##### timestamp

`string`

#### Returns

`Promise`\<`void`\>

### requestPairingCode()

> **requestPairingCode**: (`phoneNumber`, `customPairingCode`?) => `Promise`\<`string`\>

#### Parameters

##### phoneNumber

`string`

##### customPairingCode?

`string`

#### Returns

`Promise`\<`string`\>

### requestPlaceholderResend()

> **requestPlaceholderResend**: (`messageKey`, `msgData`?) => `Promise`\<`undefined` \| `string`\>

#### Parameters

##### messageKey

[`WAMessageKey`](../type-aliases/WAMessageKey.md)

##### msgData?

`Partial`\<[`WAMessage`](../type-aliases/WAMessage.md)\>

#### Returns

`Promise`\<`undefined` \| `string`\>

### resyncAppState()

> **resyncAppState**: (...`args`) => `Promise`\<`void`\>

#### Parameters

##### args

...\[readonly (`"critical_unblock_low"` \| `"regular_high"` \| `"regular_low"` \| `"critical_block"` \| `"regular"`)[], `boolean`\]

#### Returns

`Promise`\<`void`\>

### rotateSignedPreKey()

> **rotateSignedPreKey**: () => `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

### sendMessage()

> **sendMessage**: (`jid`, `content`, `options`) => `Promise`\<`undefined` \| [`WAMessage`](../type-aliases/WAMessage.md)\>

#### Parameters

##### jid

`string`

##### content

[`AnyMessageContent`](../type-aliases/AnyMessageContent.md)

##### options

[`MiscMessageGenerationOptions`](../type-aliases/MiscMessageGenerationOptions.md) = `{}`

#### Returns

`Promise`\<`undefined` \| [`WAMessage`](../type-aliases/WAMessage.md)\>

### sendMessageAck()

> **sendMessageAck**: (`node`, `errorCode`?) => `Promise`\<`void`\>

#### Parameters

##### node

[`BinaryNode`](../type-aliases/BinaryNode.md)

##### errorCode?

`number`

#### Returns

`Promise`\<`void`\>

### sendNode()

> **sendNode**: (`frame`) => `Promise`\<`void`\>

send a binary node

#### Parameters

##### frame

[`BinaryNode`](../type-aliases/BinaryNode.md)

#### Returns

`Promise`\<`void`\>

### sendPeerDataOperationMessage()

> **sendPeerDataOperationMessage**: (`pdoMessage`) => `Promise`\<`string`\>

#### Parameters

##### pdoMessage

[`IPeerDataOperationRequestMessage`](../namespaces/proto/namespaces/Message/interfaces/IPeerDataOperationRequestMessage.md)

#### Returns

`Promise`\<`string`\>

### sendPresenceUpdate()

> **sendPresenceUpdate**: (`type`, `toJid`?) => `Promise`\<`void`\>

#### Parameters

##### type

[`WAPresence`](../type-aliases/WAPresence.md)

##### toJid?

`string`

#### Returns

`Promise`\<`void`\>

### sendRawMessage()

> **sendRawMessage**: (`data`) => `Promise`\<`void`\>

send a raw buffer

#### Parameters

##### data

`Uint8Array`\<`ArrayBufferLike`\> | `Buffer`\<`ArrayBufferLike`\>

#### Returns

`Promise`\<`void`\>

### sendReceipt()

> **sendReceipt**: (`jid`, `participant`, `messageIds`, `type`) => `Promise`\<`void`\>

generic send receipt function
used for receipts of phone call, read, delivery etc.

#### Parameters

##### jid

`string`

##### participant

`undefined` | `string`

##### messageIds

`string`[]

##### type

[`MessageReceiptType`](../type-aliases/MessageReceiptType.md)

#### Returns

`Promise`\<`void`\>

### sendReceipts()

> **sendReceipts**: (`keys`, `type`) => `Promise`\<`void`\>

Correctly bulk send receipts to multiple chats, participants

#### Parameters

##### keys

[`WAMessageKey`](../type-aliases/WAMessageKey.md)[]

##### type

[`MessageReceiptType`](../type-aliases/MessageReceiptType.md)

#### Returns

`Promise`\<`void`\>

### sendRetryRequest()

> **sendRetryRequest**: (`node`, `forceIncludeKeys`) => `Promise`\<`void`\>

#### Parameters

##### node

[`BinaryNode`](../type-aliases/BinaryNode.md)

##### forceIncludeKeys

`boolean` = `false`

#### Returns

`Promise`\<`void`\>

### sendUnifiedSession()

> **sendUnifiedSession**: () => `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

### sendWAMBuffer()

> **sendWAMBuffer**: (`wamBuffer`) => `Promise`\<`any`\>

#### Parameters

##### wamBuffer

`Buffer`

#### Returns

`Promise`\<`any`\>

### serverProps

> **serverProps**: `object`

#### serverProps.lidTrustedTokenIssueToLid

> **lidTrustedTokenIssueToLid**: `boolean` = `false`

AB prop 14303: issue tctokens to LID instead of PN. WA Web default: false.

#### serverProps.privacyTokenOn1to1

> **privacyTokenOn1to1**: `boolean` = `true`

AB prop 10518: gate tctoken on 1:1 messages. Default true (safe: avoids 463).

#### serverProps.profilePicPrivacyToken

> **profilePicPrivacyToken**: `boolean` = `true`

AB prop 9666: gate tctoken on profile picture IQs. WA Web default: true.

### signalRepository

> **signalRepository**: [`SignalRepositoryWithLIDStore`](../interfaces/SignalRepositoryWithLIDStore.md)

### star()

> **star**: (`jid`, `messages`, `star`) => `Promise`\<`void`\>

Star or Unstar a message

#### Parameters

##### jid

`string`

##### messages

`object`[]

##### star

`boolean`

#### Returns

`Promise`\<`void`\>

### subscribeNewsletterUpdates()

> **subscribeNewsletterUpdates**: (`jid`) => `Promise`\<`null` \| \{ `duration`: `string`; \}\>

#### Parameters

##### jid

`string`

#### Returns

`Promise`\<`null` \| \{ `duration`: `string`; \}\>

### type

> **type**: `"md"`

### updateBlockStatus()

> **updateBlockStatus**: (`jid`, `action`) => `Promise`\<`void`\>

#### Parameters

##### jid

`string`

##### action

`"block"` | `"unblock"`

#### Returns

`Promise`\<`void`\>

### updateBussinesProfile()

> **updateBussinesProfile**: (`args`) => `Promise`\<`any`\>

#### Parameters

##### args

`UpdateBussinesProfileProps`

#### Returns

`Promise`\<`any`\>

### updateCallPrivacy()

> **updateCallPrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyCallValue`](../type-aliases/WAPrivacyCallValue.md)

#### Returns

`Promise`\<`void`\>

### updateCoverPhoto()

> **updateCoverPhoto**: (`photo`) => `Promise`\<`number`\>

#### Parameters

##### photo

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

#### Returns

`Promise`\<`number`\>

### updateDefaultDisappearingMode()

> **updateDefaultDisappearingMode**: (`duration`) => `Promise`\<`void`\>

#### Parameters

##### duration

`number`

#### Returns

`Promise`\<`void`\>

### updateDisableLinkPreviewsPrivacy()

> **updateDisableLinkPreviewsPrivacy**: (`isPreviewsDisabled`) => `Promise`\<`void`\>

Enable/Disable link preview privacy, not related to baileys link preview generation

#### Parameters

##### isPreviewsDisabled

`boolean`

#### Returns

`Promise`\<`void`\>

### updateGroupsAddPrivacy()

> **updateGroupsAddPrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyGroupAddValue`](../type-aliases/WAPrivacyGroupAddValue.md)

#### Returns

`Promise`\<`void`\>

### updateLastSeenPrivacy()

> **updateLastSeenPrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyValue`](../type-aliases/WAPrivacyValue.md)

#### Returns

`Promise`\<`void`\>

### updateMediaMessage()

> **updateMediaMessage**: (`message`) => `Promise`\<[`WAMessage`](../type-aliases/WAMessage.md)\>

#### Parameters

##### message

[`WAMessage`](../type-aliases/WAMessage.md)

#### Returns

`Promise`\<[`WAMessage`](../type-aliases/WAMessage.md)\>

### updateMemberLabel()

> **updateMemberLabel**: (`jid`, `memberLabel`) => `Promise`\<`string`\>

Update Member Label

#### Parameters

##### jid

`string`

##### memberLabel

`string`

#### Returns

`Promise`\<`string`\>

### updateMessagesPrivacy()

> **updateMessagesPrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyMessagesValue`](../type-aliases/WAPrivacyMessagesValue.md)

#### Returns

`Promise`\<`void`\>

### updateOnlinePrivacy()

> **updateOnlinePrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyOnlineValue`](../type-aliases/WAPrivacyOnlineValue.md)

#### Returns

`Promise`\<`void`\>

### updateProfileName()

> **updateProfileName**: (`name`) => `Promise`\<`void`\>

#### Parameters

##### name

`string`

#### Returns

`Promise`\<`void`\>

### updateProfilePicture()

> **updateProfilePicture**: (`jid`, `content`, `dimensions`?) => `Promise`\<`void`\>

update the profile picture for yourself or a group

#### Parameters

##### jid

`string`

##### content

[`WAMediaUpload`](../type-aliases/WAMediaUpload.md)

##### dimensions?

###### height

`number`

###### width

`number`

#### Returns

`Promise`\<`void`\>

### updateProfilePicturePrivacy()

> **updateProfilePicturePrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyValue`](../type-aliases/WAPrivacyValue.md)

#### Returns

`Promise`\<`void`\>

### updateProfileStatus()

> **updateProfileStatus**: (`status`) => `Promise`\<`void`\>

update the profile status for yourself

#### Parameters

##### status

`string`

#### Returns

`Promise`\<`void`\>

### updateReadReceiptsPrivacy()

> **updateReadReceiptsPrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAReadReceiptsValue`](../type-aliases/WAReadReceiptsValue.md)

#### Returns

`Promise`\<`void`\>

### updateServerTimeOffset()

> **updateServerTimeOffset**: (`__namedParameters`) => `void`

#### Parameters

##### \_\_namedParameters

[`BinaryNode`](../type-aliases/BinaryNode.md)

#### Returns

`void`

### updateStatusPrivacy()

> **updateStatusPrivacy**: (`value`) => `Promise`\<`void`\>

#### Parameters

##### value

[`WAPrivacyValue`](../type-aliases/WAPrivacyValue.md)

#### Returns

`Promise`\<`void`\>

### uploadPreKeys()

> **uploadPreKeys**: (`count`) => `Promise`\<`void`\>

generates and uploads a set of pre-keys to the server

#### Parameters

##### count

`number` = `MIN_PREKEY_COUNT`

#### Returns

`Promise`\<`void`\>

### uploadPreKeysToServerIfRequired()

> **uploadPreKeysToServerIfRequired**: () => `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

### upsertMessage()

> **upsertMessage**: (...`args`) => `Promise`\<`void`\>

#### Parameters

##### args

...\[[`WAMessage`](../type-aliases/WAMessage.md), [`MessageUpsertType`](../type-aliases/MessageUpsertType.md)\]

#### Returns

`Promise`\<`void`\>

### user

> **user**: `undefined` \| [`Contact`](../interfaces/Contact.md)

### userDevicesCache

> **userDevicesCache**: [`PossiblyExtendedCacheStore`](../type-aliases/PossiblyExtendedCacheStore.md) \| `NodeCache`\<[`JidWithDevice`](../type-aliases/JidWithDevice.md)[]\>

### waitForConnectionUpdate()

> **waitForConnectionUpdate**: (`check`, `timeoutMs`?) => `Promise`\<`void`\>

Waits for the connection to WA to reach a state

#### Parameters

##### check

(`u`) => `Promise`\<`undefined` \| `boolean`\>

##### timeoutMs?

`number`

#### Returns

`Promise`\<`void`\>

### waitForMessage()

> **waitForMessage**: \<`T`\>(`msgId`, `timeoutMs`) => `Promise`\<`undefined` \| `T`\>

Wait for a message with a certain tag to be received

#### Type Parameters

• **T**

#### Parameters

##### msgId

`string`

the message tag to await

##### timeoutMs

timeout after which the promise will reject

`undefined` | `number`

#### Returns

`Promise`\<`undefined` \| `T`\>

### waitForSocketOpen()

> **waitForSocketOpen**: () => `Promise`\<`void`\>

#### Returns

`Promise`\<`void`\>

### wamBuffer

> **wamBuffer**: [`BinaryInfo`](../classes/BinaryInfo.md) = `publicWAMBuffer`

### waUploadToServer

> **waUploadToServer**: [`WAMediaUploadFunction`](../type-aliases/WAMediaUploadFunction.md)

### ws

> **ws**: `WebSocketClient`
