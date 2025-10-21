#### 🎓 Professor Messer Study Notes

##  Wireless Security Settings - CompTIA Security+ SY0-701 - 4.1

[Link to video](https://youtu.be/KaqKoKNEKnE?si=QE84QZYOkCIxUcXt)

### Notes

An obvious concern with wireless networks is that the data is being passed through the air making it vulnerable to someone trying to capture that data.

The second challenge is making sure that only authorised users have access to the network.

The default way to fix these issues is encrypt the data and use the correct authentication methods with integrity controls so that we know the communication has not been modified in any way. 

MIC = message integrity check

Through the years our wireless networks were using an encryption protocol known as WPA2. But WPA2 does have a critical security concern when it comes to the initial connection to the wireless network.

PSK = pre shared key

There is a 4 way handshake that takes place on WPA2. This handshake would produce a hash of the shared key. Attackers would try get hold of this hash value and brute force their way to the original key value.

To do this, they would use GPU processing or cloud based password cracking. Once the attacker gets this key, they have access to the network.

When WPA3 was released, it also came with new technology known as GCMP block cypher mode. 

GCMP = galois/counter mode protocol

This technology offered a much stronger encryption and comes with data confidentiality with AES protocol, message integrity check with galois message authentication code (GMAC)

The authentication and 4 way handshake was also changed to a much more secure PSK authentication process.

WPA3 includes mutual authentication and creates a shared session key without sending that key across the network.

Instead, we use SAE (Simultaneous Authentication of Equals) which uses Diffie-Hellman derived key exchange with an authentication component. Everyone then has their own session key. 

This is now a IEEE standard and is referenced as the dragonfly handshake

Wireless network authentication is done in different ways. A shared password that you would provide someone if they wanted to get onto your WiFi is a pre shared key (PSK). This is very insecure.

For an organisation, we would use a more centralised authentication like 802.1x which would require a username, password, and possibly another form of authentication. 

On your home network it might be setup to use WPA3-Personal/WPA3-PSK.

In your organisation, you might be using WPA3-enterprise / WPA3-802.1X.

This centralised server is known as a AAA framework. 

It first starts with identifying who you are with identification (a username). Then we move onto the three A’s

Authentication - password. This password should only be known by you which means it’s a valid method of authentication.

Authorisation - once you gain access to the system, what resources have been allowed. 

Accounting - this is a list of metrics that is stored when you logged in that tracks who logged in, when they logged in, what data was sent and received, when they logged out.

One of the most popular authentication protocols is RADIUS (Remote Authentication Dial-in Uses Service)

When you log in, these credentials are likely being checked against a AAA server like a RADIUS server. 
