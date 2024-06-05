# Change Management
- A formal process followed to make sure that a change in either firewall configuration. modifying switch ports, etc works properly.

## Change approval process
1. Complete the request forms
2. Determine the purpose of the change.
3. Identify the scope of the change.
4. Schedule a date and time of the change.
5. Determine affected systems and the impact.
6. Analyze the risk associated with the change.
7. Get approval from the change control board.
8. Get end-user acceptance after the change is complete.

## Ownership
- An individual or entity needs to make a change, meaning that they own the process and they don't usually perform the actual change.
- The owner manages the process.

## Stakeholders
- Individuals or departments impacted by the change.

## Impact analysis
- Analyse the risks that maybe involved when making a particular change.
- Determine a risk value (high, medium, low, etc.)
- Consider the risks involved if you don't make a change.

## Test results
- Sandbox testing envirionment.

## Backout plan
- A plan to revert your changes incase the new changes fail.

## Maintenance window
- When is the change happening?

# Technical Change Management
1. Allow list/Deny list
2. Restricted activities
3. Downtime
4. Restarts
5. Legacy applications
6. Dependencies
7. Documentation
8. Version control

# Public Key Infrastructure (PKI)
- Public Key Infrastructure is a set of roles, policies, hardware, software and procedures needed to create, manage, distribute, use, store and revoke digital certificates and manage public-key encryption.

## Symmetric encryption
- This is a type of encryption key management solution where only one key (a secret key) is used to both encrypt and decrypt electronic data.

## Asymmetric encryption
-This is the process of using a public key from a public/private key pair to encrypt plaintext, and then using the corresponding private key to decrypt the ciphertext.

## Key escrow
- Someone else holds your decryption keys.

# Encrypting Stored Data
- Encryption is used to protect data from being stolen, changed, or compromised and works by scrambling data into a secret code that can only be unlocked with a unique digital key.

## Transport encryption
- Protect data traversing the network.

## Encryption algorithms
- An encryption algorithm is the method used to transform data into ciphertext.

## Cryptographic keys
- This is a string of characters used within an encryption algorithm for altering data so that it appears random.

## Key stretching
- Key stretching is a security measure that creates a random, unique, and secure password to protect sensitive information. It works by turning a user-provided password into a secret key.
- It is used to make a possibly weak key, typically a password or passphrase, more secure against a brute-force attack by increasing the resources it takes to test each possible key.

# Key Exchange
- Key exchange is a cryptography process in which cryptographic keys are exchanged between two parties, allowing them to use these keys for sharing encrypted information via a cryptographic algorithm.
1. Out-of-band key exchange - Don't use the network to send the symmetric key.
2. In-band key exchange - Sending the symmetric key over a network.
3. Use public and private key cryptography.
