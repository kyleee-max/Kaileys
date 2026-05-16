# Class: USyncUsernameProtocol

Defined in: [src/WAUSync/Protocols/USyncUsernameProtocol.ts:5](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/WAUSync/Protocols/USyncUsernameProtocol.ts#L5)

## Implements

- `USyncQueryProtocol`

## Constructors

### new USyncUsernameProtocol()

> **new USyncUsernameProtocol**(): [`USyncUsernameProtocol`](USyncUsernameProtocol.md)

#### Returns

[`USyncUsernameProtocol`](USyncUsernameProtocol.md)

## Properties

### name

> **name**: `string` = `'username'`

Defined in: [src/WAUSync/Protocols/USyncUsernameProtocol.ts:6](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/WAUSync/Protocols/USyncUsernameProtocol.ts#L6)

The name of the protocol

#### Implementation of

`USyncQueryProtocol.name`

## Methods

### getQueryElement()

> **getQueryElement**(): [`BinaryNode`](../type-aliases/BinaryNode.md)

Defined in: [src/WAUSync/Protocols/USyncUsernameProtocol.ts:8](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/WAUSync/Protocols/USyncUsernameProtocol.ts#L8)

Defines what goes inside the query part of a USyncQuery

#### Returns

[`BinaryNode`](../type-aliases/BinaryNode.md)

#### Implementation of

`USyncQueryProtocol.getQueryElement`

***

### getUserElement()

> **getUserElement**(`user`): `null` \| [`BinaryNode`](../type-aliases/BinaryNode.md)

Defined in: [src/WAUSync/Protocols/USyncUsernameProtocol.ts:15](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/WAUSync/Protocols/USyncUsernameProtocol.ts#L15)

Defines what goes inside the user part of a USyncQuery

#### Parameters

##### user

[`USyncUser`](USyncUser.md)

#### Returns

`null` \| [`BinaryNode`](../type-aliases/BinaryNode.md)

#### Implementation of

`USyncQueryProtocol.getUserElement`

***

### parser()

> **parser**(`node`): `null` \| `string`

Defined in: [src/WAUSync/Protocols/USyncUsernameProtocol.ts:20](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/WAUSync/Protocols/USyncUsernameProtocol.ts#L20)

Parse the result of the query

#### Parameters

##### node

[`BinaryNode`](../type-aliases/BinaryNode.md)

#### Returns

`null` \| `string`

Whatever the protocol is supposed to return

#### Implementation of

`USyncQueryProtocol.parser`
