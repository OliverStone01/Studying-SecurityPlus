#### 🎓 Professor Messer Study Notes

## Public Key Infrastructure - CompTIA Security+ SY0-701 - 1.4

[Link to video](https://youtu.be/KiEptGbnEBc?si=2qBOYbbPAgQ2YOJS)

### Notes

The public key infrastructure refers to procedures, hardware and software that creates, distributes, manages, stores, and revokes digital certificates.

This also refers to the binding of public keys to people or devices.

Symmetric encrpytion means to use the same key that encrypted the message to decrypt the message as well. This is sometimes refered to a `Secret key algorithm`. This ususally runs into scalability errors.

Asymmetric encryption means to use two diffrent keys. The private key and a public key. The private key is the only key that can decrypt data that is encrypted with the public key. 

As an example. If Bob wants to send Alice a message, he would encrypt the plain text message with alices public key and then he would send this encrypted data across the internet to Alice. Once Alice receives the data, she can decrypt the message using her private key.

