#### 🎓 Professor Messer Study Notes

##  Security-protocols - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/9NAKCyOtFH0?si=aiumqttjY--oqh7N)

### Notes

If you are sending data over a wired or wireless connections, it is important to make sure this data is protected.

A good way to do this is to encrypt the data so that if it is captured, it cannot be accessed in clear text by an attacker. 

The following protocols are not encrypted:
- Telnet
- FTP
- SMTP
- IMAP

You can confirm whether data is encrypted by capturing packets and looking at the data.

If you are not able to use the secure version, you are better off not using that system at all.

Telnet -> SSH
HTTP -> HTTPS
IMAP -> IMAPS
FTP -> SFTP

Port numbers are also a way to tell if the used protocol was the secure or insecure version. For example:
HTTP = port 80
HTTPS = port 443

It is important to check your transport method and not just reply on the application. For example, a network set up on 802.11 wireless. If set as open access point, none of the data is encrypted. If the device is set up as WPA3 then all data is encrypted.

You could also use a VPN which will create an encrypted tunnel for you to pass data between. 
