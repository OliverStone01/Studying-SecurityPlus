#### 🎓 Professor Messer Study Notes

## Non-repudiation - CompTIA Security+ SY0-701 - 1.2

[Link to video](https://youtu.be/XxnCxPEllMg?si=zbuV4AEnPYlT17Fi)

### Notes

Non repudiation is the act of someone not being able to deny they performed an action or sent a message.

Non repudiation can be seen in the example of signing a contract with your signature. Others can then later look at that contract and confirm it was you who signed it by looking at the signature. 

Similer methods can be seen in cryptography.

Proof of integrity means that we can verify that data has not changed. We can do this by `hashing` the data. When you hash data, the hash will return whats called a `hash value`. This value is typically the same length no matter how much or how little data you put through the hash algorithm.

If you take the same data that was previously hashed, even if the data is a whole book and you only change 1 letter on a random page, the hash value will be completly diffrent from the original hash value.

When no data has been changed, then the hash value will be the exact same.

A hash can also be called a message digest or a fingerprint.

When someone signs a document, they use their private key which only they know. Then, we can verify that signature using their public key which is known to everyone.

For example, if Alice wants to send a plaintext message to Bob, she first hashes the plaintext. Then she takes her private key and adds it to the hash value of the plain text. These values are then hashed together to create the digital signature.

Alice then sends the plaintext message and the digital signature to Bob via email or some type of digital delievery. Bob will then receive the plaintext message along with the digital signature.

For Bob to make sure that the message has not been modified in anyway and that it came from Alice, he must decrypt the digital signature using Alices public key then hash the plaintext and compare the values.

If nothing was changed and it was sent from Alice, the values will be the exact same.

