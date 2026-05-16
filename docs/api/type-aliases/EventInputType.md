# Type Alias: EventInputType

> **EventInputType**: `{ [key in Event["name"]]: { globals: (x: string) => Value; props: { [k in keyof EventByName<key>["props"]]: Value } } }` & `object`

Defined in: [src/WAM/constants.ts:22879](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/WAM/constants.ts#L22879)
