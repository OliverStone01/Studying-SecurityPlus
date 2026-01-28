#### 🎓 Professor Messer Study Notes

## Misconfiguration Vulnerabilities  - CompTIA Security+ SY0-701 - 2.3

[Link to video](https://youtu.be/NBKzlUqzVmE?si=F9uWyoFpW0gd_8yI)

### Notes

Open permissions make a very easy door for attackers to get access into a system. This is common with cloud storage.

Unsecured admin accounts like root accounts that have been set with simple passwords make it easy for attackers to brute force the password.

To prevent this attack, we can disable direct login to the root account. This is similar to windows where you sign in to your standard account and then use the admin section to run high level executables on that system.

Using insecure protocols like FTP, HTTP, IMAP, and SMTP means that data is being sent over the network without encryption and anyone can read the data in clear text. 

You can verify if data is being encrypted by capturing a packet and looking at the data. 

When you allow services on your network, you are opening a port. These ports give attackers a way in if not secured correctly. Try to limit the amount of ports open if possible. 

We can manage the network traffic going to a port using a firewall.

Always test and audit your security to make sure it is secure.











