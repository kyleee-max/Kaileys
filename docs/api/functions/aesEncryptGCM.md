# Function: aesEncryptGCM()

> **aesEncryptGCM**(`plaintext`, `key`, `iv`, `additionalData`): `Buffer`\<`ArrayBuffer`\>

Defined in: [src/Utils/crypto.ts:53](https://github.com/WhiskeySockets/Baileys/blob/28ca087cf1cbe3c05a5b704d67b3e2270d647b74/src/Utils/crypto.ts#L53)

encrypt AES 256 GCM;
where the tag tag is suffixed to the ciphertext

## Parameters

### plaintext

`Uint8Array`

### key

`Uint8Array`

### iv

`Uint8Array`

### additionalData

`Uint8Array`

## Returns

`Buffer`\<`ArrayBuffer`\>
