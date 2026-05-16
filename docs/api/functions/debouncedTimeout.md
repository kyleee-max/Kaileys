# Function: debouncedTimeout()

> **debouncedTimeout**(`intervalMs`, `task`?): `object`

Defined in: [src/Utils/generics.ts:107](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/generics.ts#L107)

## Parameters

### intervalMs

`number` = `1000`

### task?

() => `void`

## Returns

`object`

### cancel()

> **cancel**: () => `void`

#### Returns

`void`

### setInterval()

> **setInterval**: (`newInterval`) => `number`

#### Parameters

##### newInterval

`number`

#### Returns

`number`

### setTask()

> **setTask**: (`newTask`) => () => `void`

#### Parameters

##### newTask

() => `void`

#### Returns

`Function`

##### Returns

`void`

### start()

> **start**: (`newIntervalMs`?, `newTask`?) => `void`

#### Parameters

##### newIntervalMs?

`number`

##### newTask?

() => `void`

#### Returns

`void`
