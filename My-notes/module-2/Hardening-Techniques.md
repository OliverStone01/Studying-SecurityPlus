#### 🎓 Professor Messer Study Notes

## Hardening Techniques - CompTIA Security+ SY0-701 - 2.5

[Link to video](https://youtu.be/wXoC46Qr_9Q?si=tyBiohEurWhN_GPz)

### Notes

System hardening refers to keeping the operating system secure. One of the main ways to achieve this is to make sure that your system and applications are up to date.

It is important that the user accounts on these systems have minimum length and complexity password policy. 

For password complexity, the password must contain:
- Minimum password length
- Numbers
- Capital letters
- Special characters.

You should also limit accounts with their permissions.

You should also install monitoring and anti-virus/anti-malware software.

You should use full disk encryption (FDE) to limit files and data if the device is stolen. You should also use encryption on data at rest to prevent data being stolen if the data base is leaked.

You should also encrypt data over the network by using a VPN to prevent a man in the middle attack.

Currently a new method of malware detection is being developed known as Endpoint detection and response (EDR)

This detection tool uses:
- Signature detection
- Behavioural analysis
- Machine learning
- Process monitoring

This tool also can preform root cause analysis for you. If it detects something malicious, it can get more information on the running process and it will make a decision on whether it is malicious or whether it should be allowed.

Once the EDR detects the threat, it can respond by isolating the system, quarantine the threat, and rollback to a previous config.

This process can be automated using API’s and does not need a technicians intervention.

A host based firewall is able to allow or disallow incoming and outgoing traffic automatically. This is great for finding and identifying unknown processes. This system can be managed on the device or centrally from a main device.

A host-based intrusion prevention system recognises and blocks known attacks. It can detect:
- Signatures
- Heuristics
- Behavioural
- Buffer overflow attacks
- Registry updates
- Writing to files and to folders.
- Access to non-encrypted data

It is important that you keep as little ports open as possible. You can control these ports with a firewall.

Ports range from 0 to 65,535

You can use Nmap to scan ports to verify and monitor the ports.

It is vital that you change your default passwords on your systems to prevent attackers using these passwords to get into your account. If you can, add multi factor authentication.

You can protect your systems by removing unwanted software. This is because these applications may contain vulnerabilities in the code that the attackers can take advantage of.

