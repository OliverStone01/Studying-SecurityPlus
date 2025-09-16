#### 🎓 Professor Messer Study Notes

## Password attacks - CompTIA Security+ SY0-701 - 2.4

[Link to video](https://youtu.be/-ZfbifHwEVE?si=V4r7YBQBOVZNojjV)

### Notes

Storing passwords in clear text is extremely dangerous because if the data base is leaked, the attacker will have full access to everyone’s password.

If you come across a site that does this, stop using the site.

Passwords should be stored as a hash. This is because a hash cannot be reversed and if the input is not the exact same, the hash value (fingerprint) will be completely different. 

A common hash algorithm is SHA-256

A spraying attack is when an attacker will try the most common passwords on your account. If they do not succeed after 3 attempts, they will move on to another account. This is to prevent alerts being sent to the account owner.

A brute force attack is trying large amounts of passwords with every iteration to try brake into an account.

Brute force attacks online are extremely slow because the attacker can only try 3 passwords a day to prevent locking the account. What the attacker will try to do instead is get a copy of the data base with the usernames and hashed passwords and then try offline to match the hash where the attacker can attempt as many times as they like. 
