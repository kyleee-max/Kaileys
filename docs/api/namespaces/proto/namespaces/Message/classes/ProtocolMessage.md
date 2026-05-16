# Class: ProtocolMessage

Defined in: [WAProto/index.d.ts:8583](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8583)

## Implements

- [`IProtocolMessage`](../interfaces/IProtocolMessage.md)

## Constructors

### new ProtocolMessage()

> **new ProtocolMessage**(`p`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:8584](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8584)

#### Parameters

##### p?

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

## Properties

### aiPsiMetadata?

> `optional` **aiPsiMetadata**: `null` \| `Uint8Array`\<`ArrayBufferLike`\>

Defined in: [WAProto/index.d.ts:8606](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8606)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`aiPsiMetadata`](../interfaces/IProtocolMessage.md#aipsimetadata)

***

### aiQueryFanout?

> `optional` **aiQueryFanout**: `null` \| [`IAIQueryFanout`](../../../interfaces/IAIQueryFanout.md)

Defined in: [WAProto/index.d.ts:8607](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8607)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`aiQueryFanout`](../interfaces/IProtocolMessage.md#aiqueryfanout)

***

### appStateFatalExceptionNotification?

> `optional` **appStateFatalExceptionNotification**: `null` \| [`IAppStateFatalExceptionNotification`](../interfaces/IAppStateFatalExceptionNotification.md)

Defined in: [WAProto/index.d.ts:8593](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8593)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateFatalExceptionNotification`](../interfaces/IProtocolMessage.md#appstatefatalexceptionnotification)

***

### appStateSyncKeyRequest?

> `optional` **appStateSyncKeyRequest**: `null` \| [`IAppStateSyncKeyRequest`](../interfaces/IAppStateSyncKeyRequest.md)

Defined in: [WAProto/index.d.ts:8591](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8591)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateSyncKeyRequest`](../interfaces/IProtocolMessage.md#appstatesynckeyrequest)

***

### appStateSyncKeyShare?

> `optional` **appStateSyncKeyShare**: `null` \| [`IAppStateSyncKeyShare`](../interfaces/IAppStateSyncKeyShare.md)

Defined in: [WAProto/index.d.ts:8590](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8590)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`appStateSyncKeyShare`](../interfaces/IProtocolMessage.md#appstatesynckeyshare)

***

### botFeedbackMessage?

> `optional` **botFeedbackMessage**: `null` \| [`IBotFeedbackMessage`](../../../interfaces/IBotFeedbackMessage.md)

Defined in: [WAProto/index.d.ts:8599](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8599)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`botFeedbackMessage`](../interfaces/IProtocolMessage.md#botfeedbackmessage)

***

### cloudApiThreadControlNotification?

> `optional` **cloudApiThreadControlNotification**: `null` \| [`ICloudAPIThreadControlNotification`](../interfaces/ICloudAPIThreadControlNotification.md)

Defined in: [WAProto/index.d.ts:8603](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8603)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`cloudApiThreadControlNotification`](../interfaces/IProtocolMessage.md#cloudapithreadcontrolnotification)

***

### disappearingMode?

> `optional` **disappearingMode**: `null` \| [`IDisappearingMode`](../../../interfaces/IDisappearingMode.md)

Defined in: [WAProto/index.d.ts:8594](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8594)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`disappearingMode`](../interfaces/IProtocolMessage.md#disappearingmode)

***

### editedMessage?

> `optional` **editedMessage**: `null` \| [`IMessage`](../../../interfaces/IMessage.md)

Defined in: [WAProto/index.d.ts:8595](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8595)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`editedMessage`](../interfaces/IProtocolMessage.md#editedmessage)

***

### ephemeralExpiration?

> `optional` **ephemeralExpiration**: `null` \| `number`

Defined in: [WAProto/index.d.ts:8587](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8587)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`ephemeralExpiration`](../interfaces/IProtocolMessage.md#ephemeralexpiration)

***

### ephemeralSettingTimestamp?

> `optional` **ephemeralSettingTimestamp**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8588](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8588)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`ephemeralSettingTimestamp`](../interfaces/IProtocolMessage.md#ephemeralsettingtimestamp)

***

### historySyncNotification?

> `optional` **historySyncNotification**: `null` \| [`IHistorySyncNotification`](../interfaces/IHistorySyncNotification.md)

Defined in: [WAProto/index.d.ts:8589](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8589)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`historySyncNotification`](../interfaces/IProtocolMessage.md#historysyncnotification)

***

### initialSecurityNotificationSettingSync?

> `optional` **initialSecurityNotificationSettingSync**: `null` \| [`IInitialSecurityNotificationSettingSync`](../interfaces/IInitialSecurityNotificationSettingSync.md)

Defined in: [WAProto/index.d.ts:8592](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8592)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`initialSecurityNotificationSettingSync`](../interfaces/IProtocolMessage.md#initialsecuritynotificationsettingsync)

***

### invokerJid?

> `optional` **invokerJid**: `null` \| `string`

Defined in: [WAProto/index.d.ts:8600](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8600)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`invokerJid`](../interfaces/IProtocolMessage.md#invokerjid)

***

### key?

> `optional` **key**: `null` \| [`IMessageKey`](../../../interfaces/IMessageKey.md)

Defined in: [WAProto/index.d.ts:8585](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8585)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`key`](../interfaces/IProtocolMessage.md#key)

***

### lidMigrationMappingSyncMessage?

> `optional` **lidMigrationMappingSyncMessage**: `null` \| [`ILIDMigrationMappingSyncMessage`](../../../interfaces/ILIDMigrationMappingSyncMessage.md)

Defined in: [WAProto/index.d.ts:8604](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8604)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`lidMigrationMappingSyncMessage`](../interfaces/IProtocolMessage.md#lidmigrationmappingsyncmessage)

***

### limitSharing?

> `optional` **limitSharing**: `null` \| [`ILimitSharing`](../../../interfaces/ILimitSharing.md)

Defined in: [WAProto/index.d.ts:8605](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8605)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`limitSharing`](../interfaces/IProtocolMessage.md#limitsharing)

***

### mediaNotifyMessage?

> `optional` **mediaNotifyMessage**: `null` \| [`IMediaNotifyMessage`](../../../interfaces/IMediaNotifyMessage.md)

Defined in: [WAProto/index.d.ts:8602](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8602)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`mediaNotifyMessage`](../interfaces/IProtocolMessage.md#medianotifymessage)

***

### memberLabel?

> `optional` **memberLabel**: `null` \| [`IMemberLabel`](../../../interfaces/IMemberLabel.md)

Defined in: [WAProto/index.d.ts:8608](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8608)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`memberLabel`](../interfaces/IProtocolMessage.md#memberlabel)

***

### peerDataOperationRequestMessage?

> `optional` **peerDataOperationRequestMessage**: `null` \| [`IPeerDataOperationRequestMessage`](../interfaces/IPeerDataOperationRequestMessage.md)

Defined in: [WAProto/index.d.ts:8597](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8597)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`peerDataOperationRequestMessage`](../interfaces/IProtocolMessage.md#peerdataoperationrequestmessage)

***

### peerDataOperationRequestResponseMessage?

> `optional` **peerDataOperationRequestResponseMessage**: `null` \| [`IPeerDataOperationRequestResponseMessage`](../interfaces/IPeerDataOperationRequestResponseMessage.md)

Defined in: [WAProto/index.d.ts:8598](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8598)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`peerDataOperationRequestResponseMessage`](../interfaces/IProtocolMessage.md#peerdataoperationrequestresponsemessage)

***

### requestWelcomeMessageMetadata?

> `optional` **requestWelcomeMessageMetadata**: `null` \| [`IRequestWelcomeMessageMetadata`](../interfaces/IRequestWelcomeMessageMetadata.md)

Defined in: [WAProto/index.d.ts:8601](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8601)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`requestWelcomeMessageMetadata`](../interfaces/IProtocolMessage.md#requestwelcomemessagemetadata)

***

### timestampMs?

> `optional` **timestampMs**: `null` \| `number` \| `Long`

Defined in: [WAProto/index.d.ts:8596](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8596)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`timestampMs`](../interfaces/IProtocolMessage.md#timestampms)

***

### type?

> `optional` **type**: `null` \| [`Type`](../namespaces/ProtocolMessage/enumerations/Type.md)

Defined in: [WAProto/index.d.ts:8586](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8586)

#### Implementation of

[`IProtocolMessage`](../interfaces/IProtocolMessage.md).[`type`](../interfaces/IProtocolMessage.md#type)

## Methods

### toJSON()

> **toJSON**(): `object`

Defined in: [WAProto/index.d.ts:8614](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8614)

#### Returns

`object`

***

### create()

> `static` **create**(`properties`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:8609](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8609)

#### Parameters

##### properties?

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

***

### decode()

> `static` **decode**(`r`, `l`?): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:8611](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8611)

#### Parameters

##### r

`Uint8Array`\<`ArrayBufferLike`\> | `Reader`

##### l?

`number`

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

***

### encode()

> `static` **encode**(`m`, `w`?): `Writer`

Defined in: [WAProto/index.d.ts:8610](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8610)

#### Parameters

##### m

[`IProtocolMessage`](../interfaces/IProtocolMessage.md)

##### w?

`Writer`

#### Returns

`Writer`

***

### fromObject()

> `static` **fromObject**(`d`): [`ProtocolMessage`](ProtocolMessage.md)

Defined in: [WAProto/index.d.ts:8612](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8612)

#### Parameters

##### d

#### Returns

[`ProtocolMessage`](ProtocolMessage.md)

***

### getTypeUrl()

> `static` **getTypeUrl**(`typeUrlPrefix`?): `string`

Defined in: [WAProto/index.d.ts:8615](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8615)

#### Parameters

##### typeUrlPrefix?

`string`

#### Returns

`string`

***

### toObject()

> `static` **toObject**(`m`, `o`?): `object`

Defined in: [WAProto/index.d.ts:8613](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/WAProto/index.d.ts#L8613)

#### Parameters

##### m

[`ProtocolMessage`](ProtocolMessage.md)

##### o?

`IConversionOptions`

#### Returns

`object`
