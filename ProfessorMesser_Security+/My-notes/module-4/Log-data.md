#### 🎓 Professor Messer Study Notes

##  Log Data - CompTIA Security+ SY0-701 - 4.9

[Link to video](https://youtu.be/EDru1LTYDJw?si=gcLgq2TXc-WXkcmD)

### Notes

Log data is one of the most powerful tools we have in security. Every device, every server, and every application running on our networks is generating logs. Inside those logs is lots of information such as traffic flows that were blocked/allowed, exploit attempts stopped, and much more.

The firewall logs track every connecting showing us the source and destination IP address, ports in use, and whether traffic was allowed or blocked. 

Application logs can be found in the event viewer on Windows and for Linux and MacOS, they can be found at /var/log. These logs track system events, process activity, password changes, and authentication details. All this data can be centralised using a SIEM.

Endpoints also store logs that include login attempts, system processes, directory services, and account lockouts.

Operating systems contain security logs which can flag brute force attacks, changes to critical system files, and unusual service activity. This is sometimes what gives us the first warning of an attack in progress.

WE also gather data from intrusion prevention and detection systems. These record known vulnerabilities and attack signatures. We may also collect data from network infrastructure devices like routers and switches which will show authentication failures and attacks such as TCP SYN floods.

Metadata is the hidden information inside documents, emails, pictures, and web traffic. For example, an email header may reveal which server it passed through, a smartphone can expose a GPS coordinate.

Vulnerability scans also generate logs. These help us find unpatched systems or misconfiguration.

With this many logs and this much data, we use SIEM to automate the process and generate a detailed report or provide dashboards that give us real time updates of the networks health.

Where we need to see the deepest level of visibility, we can use a packet capture tool like Wireshark that allows us to see each frame and every header.

Log data is the nervous system of cybersecurity telling us information on our security.
