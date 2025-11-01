#### 🎓 Professor Messer Study Notes

##  Incident Response - CompTIA Security+ SY0-701 - 4.8

[Link to video](https://youtu.be/X2UiMLxRdhE?si=v4KfmhoYxBtizVno)

### Notes

Security incidents are inevitable. As a security professional, we must be ready for anything. NIST gives us a clear framework in Special Publication 800-61 revision 2, the Computer Security Incident Handling Guide. It breaks the lifecycle into phases:
- Preparation
- Detecting and analysis
- Containment
- Eradication
- Recovery
- Post-incident activities

Preparation is everything. Keep communication lists updated. Maintain an incident “go bag” with laptops, forensic software, removable media, and imaging tools. Have documentation, network diagrams file hashes, and baseline configurations ready. Store clean OS images and application installs. Have clear policies and procedures.

Attacks happen all the time, the challenge is telling the background noise apart from real compromises. Logs, alerts and monitoring tools help to spot changes in systems. Sometimes attacks even announce the attack themselves.

If you confirm an attack has occurred, act fast. Don’t wait to see what happens. You may need to isolate the malware using sandboxing or by taking the system offline. It is important to remember that malware can behave differently if it detects it is in a virtual environment.

Recovery is the act of restoring from clean sources. It involves wiping systems, reinstalling operating systems, restore from backups, disable compromised accounts, and patch vulnerabilities.

Once the attack is cleared, reflection begins. It’s important to meet with the relevant teams and ask what happened, what was the timeline, how well did the systems hold up, did we miss indicators, and what must change for next time. These lessons will feed back into planning and training.

Training happens before the incident not during. It is important that everyone knows their roles and the processes they must follow in a response situation.
