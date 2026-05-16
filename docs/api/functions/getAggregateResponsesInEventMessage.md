# Function: getAggregateResponsesInEventMessage()

> **getAggregateResponsesInEventMessage**(`msg`, `meId`?): `ResponseAggregation`[]

Defined in: [src/Utils/messages.ts:992](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/messages.ts#L992)

Aggregates all event responses in an event message.

## Parameters

### msg

`Pick`\<[`WAMessage`](../type-aliases/WAMessage.md), `"eventResponses"`\>

the event creation message

### meId?

`string`

your jid

## Returns

`ResponseAggregation`[]

A list of response types & their responders
