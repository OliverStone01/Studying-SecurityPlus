#### 🎓 Professor Messer Study Notes

## Replay Attacks - CompTIA Security+ SY0-701 - 2.4

[Link to video](https://youtu.be/ai6qS13gKRo?si=xaFGDW8zn2Z5erdt)

### Notes

A replay attack is where the attacker will take advantage of data being sent between the network and your device. 

To do this, they will use a network tap to receive the data and possibly use ARP poisoning to modify the data.

Once the attack has this information, they can replay it back to the server and pretend to be the user. 

A common attack is a pass the hash attack. This is where the attacker sets up a way for them to receive the username and the hashed password when the user signs in.

Once they have this information, they can replay this message to the server and sign in. 

A method to protect against this attack is to make sure all your data is encrypted when travelling across the network. Including salting on sign in.

Another piece of data that an attacker may want is your cookies. These cookies act as a quick verification to log into specific sites 

Session hijacking is where the attacker steals the session ID from the cookies and is able to sign in. 

This information is sent back between headers in the browser and could be captured using a packet capture tool like wire shark.

Attackers may use header manipulation to run cross site scripting attacks or to modify cookies.

To protect against these attacks, use end to end encryption. If you cannot do end to end encryption, encrypt from your device to a VPN concentrator.

