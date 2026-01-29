#### 🎓 Professor Messer Study Notes

##  Endpoint Security - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/83pCkSSj1IQ?si=AEJOJQgBtjFHpgsx)

### Notes


Endpoint security is the security of the device that users rely on every day (Desktops, laptops, tablets, and smartphones). Applications running on them may be exploited to steal sensitive data. Defending endpoints requires a layered approach which is called defense in depth.

At the edge of network where the internal system meets the outside internet, we usually place a firewall. Firewalls enforce security rules. On top of the firewall, we apply access control. These rules can restrict data access by users, groups, location, or application. Administrators can update or remove these rules depending on the security posture.

A posture assessment checks to ensure devices are properly secured before they are allowed full access to the network. This might check that antivirus is installed and up to date, applications are patched, full disk encryption is enables, and that a valid company certificate is present. If a system doesn’t pass, we can quarantine it by placing it on a limited VLAN and guiding the user to bring it back into compliance.

A persistent agent is installed permanently on a device and is continuously monitoring the system.

A dissolvable agent runs temporarily during login and then removes itself.

A agent-less network access control often integrated with Active Directory checks compliance only during login or logout.

Traditional anti-virus struggles because millions of new malware variants are created daily. EDR (Endpoint Detection and Response) extends beyond signature based detection. It uses behavioral analysis, process monitoring, and machine learning to identify threats. EDR can also provide root-cause analysis. This includes figuring out how the threat got in and removing it and prevent it getting back in in the future. 

EDR systems are automatic.

A more advanced approach is XDR (Extended Detection and Response). A XDR pulls in data from multiple systems, not just a single endpoint. By collecting information from endpoints, networks, and user activity, XDR’s can reduce false positives and speed up investigations.

The goal of EDR and XDR is to detect malicious activity quickly, stop it in real time, and prevent it from becoming a larger problem.
