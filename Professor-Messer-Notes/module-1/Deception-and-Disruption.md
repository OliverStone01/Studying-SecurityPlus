#### 🎓 Professor Messer Study Notes

## Deception and Disruption - CompTIA Security+ SY0-701 - 1.2

[Link to video](https://youtu.be/X_qfMVty4ts?si=sR8W08FxN1m-dqtq)

### Notes

A honeypot is a way to attract the bad guys (Typically automatic bots) to see what type of attackes they are using so that you can find ways to prevent them.

To make a honeypot more realistic to trick the attackers to believe they have found a system. We create a honeynet which consists of fake servers, workstations, routers, switches, and firewalls.

We can also go a step further and create honeyfiles that look like they contain important information such as a file called `passwords.txt`. This will keep the attackers busy for a long time as they believe they now have access to your passwords.

These files are more like bear traps and you dont want them to be found as this implies an attacker is in the system. You can add alerts to the file so that you can be told when it has been found and opened.

Honeytokens are traceable data that we can use to detect if someone tried to use. For example, we can set up a fake API credential that when used, tells us who is using it and notifies when its being used.

Another example is a fake email address. We can check where this email address pops up so we can detect who is using it. 













