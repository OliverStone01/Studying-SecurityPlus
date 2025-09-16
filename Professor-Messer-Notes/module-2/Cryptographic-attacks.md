#### 🎓 Professor Messer Study Notes

## Buffer Overflow - CompTIA Security+ SY0-701 - 2.2

[Link to video](https://youtu.be/7aJaEQy6Yoc?si=QPApK35hDBA4HtXd)

### Notes

The part of encryption that determines how secure the encryption is, is the key itself.

With cryptography, everything about how the cryptography works is shared with every one. This is what allows us to check how safe it is. 

Implementing cryptography incorrectly is the biggest vulnerability in cryptography.

A birthday attack commonly known as a hash collision is when two different values create the same hash. 

To make this less likely, we increase the hash output size. 

This is the reason we no longer use MD5 (Message Digest version 5)

A downgrade attack is an example of perfectly good algorithm but the implementation causes many vulnerabilities.

SSL stripping is the combination of a downgrade attack and an on path attack. This strips away the encryption from HTTPS.

The striping reverts https into http
