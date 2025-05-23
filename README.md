# File-encryption-decryption
This project is a simple command-line utility written in Python for encrypting and decrypting files using symmetric encryption with the cryptography library. It allows users to:  
- Generate a secure encryption key.
- Encrypt any file by specifying its name.
- Decrypt an encrypted file using the correct key.

Features
Uses Fernet encryption for strong symmetric key encryption.

Saves the encryption key in a file (Secret.key) for later use.

Includes example image files and a PowerPoint presentation for demonstration or documentation purposes.

How to Use
Run the script: python main.py

Choose to encrypt or decrypt a file.

Follow the prompts to specify the filename and operation.

Note: Ensure Secret.key is kept secure; losing it means you cannot decrypt your files.
