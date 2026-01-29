#### 🎓 Professor Messer Study Notes

##  Monitoring Data - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/ZDJ-BLPLWq4?si=gRKsJn6PBfp0tCpX)

### Notes

When managing a server or an application, some files almost never change. It’s critical to know if these core files are suddenly modified. For this we can use file integrity monitoring (FIM).

On windows, this is handled by the system file checker (SFC). This file checker scans critical system files, verifies their integrity, and replaces any files that have been altered. On Linux, a common tool is Tripwire which can provide real time alerts when files change.

An advanced solution includes host-based intrusion prevention system which runs directly on the operating system. This gives them visibility into local file changes as well as blocking known attack.

A critical defense system is a Data Loss Prevention (DLP). These systems are designed to stop sensitive data from leaking out. These are categorised as monitoring data in motion, data at rest, and data in use.

DLPs can run in different forms. Network-based DLP inspects traffic in real time. Endpoint or host-based DLPs run on an individual systems often blocking risky transfers such as a USB drive. Cloud-based DLP solutions monitor and block sensitive uploads into SaaS platforms and cloud storage.

One of the biggest channels for data loss is email. Email-based DLP solutions scan outgoing messages for sensitive information such as social security numbers, tax forms, or financial data.

File integrity monitoring protects the core files on your system.

Data loss prevention protects sensitive data.
