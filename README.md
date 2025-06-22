Custom File Encryption/Decryption Tool

> Secure File Encryption/Decryption Tool (AES-256)
A command-line utility in Python for advanced file encryption and decryption. It employs AES-256 symmetric encryption
with robust PBKDF2 key derivation from a user-defined passphrase, ensuring strong data confidentiality.

 Features
Encrypts files using AES-256 in CBC mode.
Securely derives keys from passwords using PBKDF2 with SHA256.
Generates unique cryptographic salts and Initialization Vectors (IVs) per encryption.
Supports large files by processing data in chunks.
Includes comprehensive error handling for file operations and password validation.

> Technologies
Python 3.x
cryptography library (AES, PBKDF2, padding primitives)
secrets module (Cryptographically strong randomness)

 Getting Started
Clone the repository (ensure encrypt_tool.py is present).
Create and activate a virtual environment (as above).
Install dependencies:
pip install cryptography

Run the tool:
python encrypt_tool.py

Follow the interactive prompts to encrypt or decrypt files.
