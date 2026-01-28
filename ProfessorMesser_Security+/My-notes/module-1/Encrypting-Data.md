#### 🎓 Professor Messer Study Notes

## Encrypting data - CompTIA Security+ SY0-701 - 1.4

[Link to video](https://youtu.be/xHAMEF7-inQ?si=Ut-0rT0nozCPds_Y)

### Notes

We can protect our data by encrypting it at rest. This can be done on a SSD, hard drive, USB drive, cloud storage, and so on.

We can either encrypt specific files or we can do a `Full-disk` and `partition/volume` encryption. In windows, we can use Bitlocker. On mac, we can use FileVault.

For encrypting individual files, we can use EFS (Encrypting File System)

For database data, we can use `transparent encryption` which encrypts all database information with a symmetric key. This means any data we pull or push to the database is encrypted or decrypted with the same key.

Some databases store some data that needs to be protected and other data that does'nt. We can use whats called `Record-level encryption` to encrypt individual columns and use separate symmetric keys for each column.

It is important to encrypt your data in transport. To do this over a browser, we can use HTTPS which encrypts all data being sent to and from the browser.

We can also create a encrypted tunnel between two networks using a VPN.

To be able to decrypt the encrypted data, you must use the same encryption algorithm. 

The algorithm can be known to all. The keys are what must be kept secret.

The larger the key length, the stronger and more secure the key is.

We can stretch keys to make them more secure. To do this we can preform multiple hashes on the key to make it more and more secure. 


