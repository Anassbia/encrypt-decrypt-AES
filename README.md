To use this program,replace the value of key with a 16, 24, or 32-byte key. Then, call the encrypt_file function to encrypt a file and the decrypt_file function to decrypt it.
The chunksize parameter controls how many bytes are read and written at a time, and can be adjusted for performance.

this program uses CBC mode, which requires an initialization vector (IV) that must be unique for each encryption operation.
The program generates a random IV and writes it to the beginning of the encrypted file, so it can be used during decryption.
