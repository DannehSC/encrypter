# Installation
Do `lit install DannehSC/encrypter`
# Usage
Initial require:
`local Encyption_Library=require("encrypter")`
Each function usage:
*Randomizer*
`local Random_Key=Encryption_Library.Randomizer(50)`
*Keygen*
`local Other_Key=Encryption_Library.Keygen()`
*Encrypt*
`local Data='Hello, this is a coding example.'
local Encrypted_Data=Encryption_Library.Encrypt(data,Random_Key)`
Returns the encrypted data.
*Decrypt*
`local Decrypted_Data=Encryption_Library.Decrypt(Encrypted_Data,Random_Key)`
Returns "Hello, this is a coding example."
