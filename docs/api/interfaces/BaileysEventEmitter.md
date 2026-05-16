# Interface: BaileysEventEmitter

Defined in: [src/Types/Events.ts:174](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Events.ts#L174)

## Methods

### emit()

> **emit**\<`T`\>(`event`, `arg`): `boolean`

Defined in: [src/Types/Events.ts:178](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Events.ts#L178)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

##### arg

[`BaileysEventMap`](../type-aliases/BaileysEventMap.md)\[`T`\]

#### Returns

`boolean`

***

### off()

> **off**\<`T`\>(`event`, `listener`): `void`

Defined in: [src/Types/Events.ts:176](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Events.ts#L176)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

##### listener

(`arg`) => `void`

#### Returns

`void`

***

### on()

> **on**\<`T`\>(`event`, `listener`): `void`

Defined in: [src/Types/Events.ts:175](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Events.ts#L175)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

##### listener

(`arg`) => `void`

#### Returns

`void`

***

### removeAllListeners()

> **removeAllListeners**\<`T`\>(`event`): `void`

Defined in: [src/Types/Events.ts:177](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Types/Events.ts#L177)

#### Type Parameters

• **T** *extends* keyof [`BaileysEventMap`](../type-aliases/BaileysEventMap.md)

#### Parameters

##### event

`T`

#### Returns

`void`
