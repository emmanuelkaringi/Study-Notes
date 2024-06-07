# Encryption Technologies

## Trusted Platform Module (TPM)
- A TPM chip is a secure crypto-processor that is designed to carry out cryptographic operations.
## Hardware Security Module (HSM)
- Hardware Security Modules (HSMs) are hardened, tamper-resistant hardware devices that strengthen encryption practices by generating keys, encrypting and decrypting data, and creating and verifying digital signatures.

**An HSM is a removable unit that runs on its own, while a TPM is a chip on your motherboard that can encrypt an entire laptop or desktop disk.**

## Key management system
- Key management refers to management of cryptographic keys in a cryptosystem. This includes dealing with the generation, exchange, storage, use, crypto-shredding (destruction) and replacement of keys. It includes cryptographic protocol design, key servers, user procedures, and other relevant protocols.

## Secure enclave
- This is a proteced area for our secrets, often implemented as a hardware processor. It is isolated from the main processor.
- It provides extensive security features:
	1. Has its own boot ROM.
	2. Monitors the system boot process.
	3. True random number generator.
	4. Real-time memory encryption.

# Obfuscation
- This is the process of making something unclear.
*Example: Steganography - Hiding information inside of an image.*
## Common steganography techniques
1. Network based - Embed messages in TCP packets.
2. Use an image - Embed the message in the image itself.
3. Invisible watermarks - Yellow dots on printers.
4. Audio steganography - Interlace a secret message within an audio.
5. Video steganography - Interlace a secret message within a video.
## Tokenization
- Replace sensitive data with a non-sensitive placeholder. eg. SSN 266-12-1112 is now 691-61-8539
- Commonly used in credit card processing.
## Data masking
- Data obfuscation- Hiding some of the original data.

# Hashing and Digital Signatures
## Hashes
- Act of representing data as a short string of text. Also known as a message digest or a fingerprint.
- Used to store passwords/confidentiality.
- Can be used to verify a downloaded document is the same as the original.
- Can be used to create a digital signature.
- The hash should be unique i.e. Different inputs should never create the same hash, if they do, that is a collision.

## Digital signatures
- A digital signature confirms that the information originated from the signer and has not been altered.

# Blockchain Technology
- A blockchain is a distributed ledger with growing lists of records (blocks) that are securely linked together via cryptographic hashes.
- Everyone on the blockchain network maintains the ledger.

# Certificates
## Digital certificates
- A digital certificate is a file or electronic password that proves the authenticity of a device, server, or user through the use of cryptography and the public key infrastructure (PKI).
- Digital certificate authentication helps organizations ensure that only trusted devices and users can connect to their networks.
## Root of trust
- Root of Trust (RoT) is a source that can always be trusted within a cryptographic system.
