#### 🎓 Professor Messer Study Notes

## Viruses and Worms  - CompTIA Security+ SY0-701 - 2.4

[Link to video](https://youtu.be/Su8ANmAoerU?si=Wk8ekU6NvHnp_Zqg)

### Notes

A virus is able to replicate itself from one computer to another. It all starts when someone clicks a link or executes a program.

The virus reproduces through file systems or via the network.

Viruses may or may not cause issues on your device.

Anti-virus software is always running and is detecting when executables are run to recognise any software that has been identified as malicious.

The signature file is where the anti-virus checks against to detect viruses.

There are viruses that run when programs are run, in the boot of a system, script viruses that run in the operating system, and macro viruses that are common in microsoft office.

A fileless virus is a well hidden because it does not write or change files in the drive which is where the anti virus is checking. A fileless virus works in the memory. 

A fileless virus usually starts with a link in an email, the link will then take you to a website that exploits a vulnerability on your operating system. Then the virus begins to run other applications like powershell and downloads payloads into ram. The scripts are run and executed in memory, exfiltrates data, and damages files. Finally, the virus makes an auto start to the device registry. 

Worms are malware that self replicate without the user needing the user to do anything. Worms can take over an entire network extremely quickly.

Firewalls can IDS/IPS can mitigate many worm infestations.

