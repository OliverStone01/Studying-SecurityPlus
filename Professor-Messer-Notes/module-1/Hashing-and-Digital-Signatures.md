#### 🎓 Professor Messer Study Notes

## Hashing and digital signatures - CompTIA Security+ SY0-701 - 1.4

[Link to video](https://youtu.be/EcGmQjl6XEo?si=aBgW-jt257vqTk1E)

### Notes

A hash is a short string that represents data at any length. This hash is not reversible and the original text is not able to be recovered just using the hash.

Hashes are used as fingerprints and for proving non reputations. We can hash a file and store the hash. Later when we come back to that file we can hash it again and if the hashes are not the same, then the file has been edited.

Hashes can also be used when creating digital signatures.

A common hashing algorithm is SHA256. This hash takes 256 bits and returns 64 hexadimal

Collisions are when two completely different pieces of data create the same hash value. This is something we really want to avoid

This is the same reason we no longer use the MD5 algorithm as it has a collision vulnerability. 

Hashing is used to verify documents when downloading them off the Internet. 

The other main use is passwords. We would never store passwords in plain text because if the database got leaked, your password would be revealed. We also don’t store passwords encrypted because someone could decrypt the password.

Instead when you create a password. The plain text is hashed and the hash value is what is stored in the database. Then when you come to sign back into that account, your plain text input is hashed and compared against the hash value in the database.

When we store passwords, we also add a salt. This is a piece of information that is added onto your password before it is hashed to make it more difficult. This also prevents data leaks where people have used the same password on many sites from exposing passwords on other sites. 

A rainbow table attack is where attackers have a pre made list of hashes that they can use to compare hashes from the database to find your password. This is why we use a salt. 

A hash is also used when making a digital signature. A digital signature is used to prove that a message was sent from a person. 

A message is signed with the private key and the verified with the users public key.
