#### 🎓 Professor Messer Study Notes

##  Digital Forensics - CompTIA Security+ SY0-701 - 4.8

[Link to video](https://youtu.be/UtDWApdO8Zk?si=_snl5iwryp8ynnFH)

### Notes


Digital forensics is the process of collecting, preserving, and analysing data. Not only are we trying to understand what happened, but also to improve defences and when needed, to support legal proceedings.

The key is best practices. RFC 3227 provides industry guidelines on evidence collection and archiving. Security professionals must carefully document how evidence was acquired, kept intact, and how you maintained its integrity.

A common request is a legal hold. This comes from a lawyer or court, instructing a custodian to preserve specific electronically stored information (ESI). Data is then collected into a secure repository.

Preservation is critical. Evidence must remain in its original state. That’s why we use chain of custody procedures. In the physical world, evidence is sealed in bags. In the digital world, hashes and digital signatures verify integrity. Each person who accesses the data must be logged, so later we can prove nothing was tampered with.

Data can come from many sources:
- Disks, memory, firmware
- Network devices, firewall logs, servers
- Virtual machines via snapshots
- Less obvious places, like. Recycle bins, temporary files, or saved browser credentials

Every source requires documentation and chain of custody.

After collection is reporting. Analysts write detailed notes describing the acquisition process, integrity checks, and steps taken. These reports often include:
- A summary of the events and why data was acquired
- A step-by-step record of acquired
- Integrity verification details
- Analysis and conclusions on how the evidence is connected to the incident.

Original data is preserved while analysis is performed on exact copies. This protects the evidence from accidental modifications.

E-discovery is about collection.

Digital forensics must be accurate and must keep integrity. Evidence must be properly acquired and preserved.
