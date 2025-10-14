#### 🎓 Professor Messer Study Notes

##  Protecting Data - CompTIA Security+ SY0-701 - 3.3

[Link to video](https://youtu.be/leX_Qa7wqB4?si=SfhhcjAUsP3ttq5j)

### Notes

Geographic restrictions are ways to restrict users depending on their location. We can find this location based on their IP subnet. This can be difficult to do with mobile devices because they can be located virtually anywhere. 

What we will do is additional checks like GPS or 802.11 wireless database.

Geofencing is describing where the use must be inside to be able to access the site or server. Anything outside of this fence will be restricted.

Protecting data is a primary task. The issue is data is everywhere. This is why we need to use many different types of security methods so that no matter where the data is, it is protected.

This might look like encryption on all data and setting data permissions so that only specific users can access the data.

Encryption is taking plain text and turning it into cypher text. Once the data has been sent to the correct user or device, it then needs to be decrypted back into plain text.

Hashing is a way of representing data in a way that cannot be repeated without the exact data that created the hash in the first place. This is sometimes known as a message digest and is used for storing passwords in a safe way because the user can enter their password and server will check if the hash of the password matches the hash value in the data base then the password is correct. If an attacker gets ahold of this database, there is no way for them to reverse the hash.

If you manage to use two different types of input that generate the same hash value then you have found a collision. 

Obfuscation is the act of taking something that is easy to read and turning it into something that is difficult to understand. 

This is sometimes seen with developers when they give codebase to someone they might obfuscate and the code so that they can protect their codebase. The obfuscated code will still work completely normal. Attackers may use obfuscation to hide what’s happening in an attack.

Masking is when you hide some of the original data. This can be seen with receipts where the long card number is replaced with asterisk * and the last 4 digits remain. 

Tokenisation is taking your original card data and linking it with a temporary one time use token. You can then go into a store and use this token to tell the vendor this is the token my card details are linked to. The vendor can then use this token to get access to your payment information and charge you for the service or product. This token is then scrapped and replaced with a new token which means attackers cannot capture this token and reuse it.

If your organisation is attacked, you want to limit the amount of data that an attacker is able to access. To do this, we can use segmentation to split up the network and only allow access to specific areas to specific users.

This will prevent attackers from gaining access to your entire network if they get in at one place.

Permissions restriction are restrictions given to each users account. For accounts with less restrictions, you might be required to enter multiple types of authentication to prove you are that user.
