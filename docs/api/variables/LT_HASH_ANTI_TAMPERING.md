# Variable: LT\_HASH\_ANTI\_TAMPERING

> `const` **LT\_HASH\_ANTI\_TAMPERING**: `LTHashAntiTampering`

Defined in: [src/Utils/lt-hash.ts:8](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/lt-hash.ts#L8)

LT Hash is a summation based hash algorithm that maintains the integrity of a piece of data
over a series of mutations. You can add/remove mutations and it'll return a hash equal to
if the same series of mutations was made sequentially.
