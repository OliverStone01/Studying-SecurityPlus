#### 🎓 Professor Messer Study Notes

##  Security Tools - CompTIA Security+ SY0-701 - num

[Link to video](https://youtu.be/nNiNTviiacU?si=DgTRXzK7bIQNdzZp)

### Notes

The issue with having many different types of security devices is that they might all identify the same vulnerability but they might all have a different name for it.

SCAP (Security content automation protocol) which is maintained by NIST (National institution of standards and technology). This protocol converts all these different notifications into one language and allows the systems to be able to highlight these as one vulnerability. 

SCAP content can be shared between tools which makes it easier to find a patch and fix the vulnerability.

This can be very useful if you have a large environment to take care of. This also allows us to completely automate ongoing monitoring, notification and alerting, and remediation of noncompliant systems.

Benchmarks are a the bare minimum of security. It is best to use best practices on any device or software you have. 

You can find these benchmarks at the CIS (Center of internet security) website. 

You can use agents to see if devices are compliant. Agents are typically monitoring for real-time notification and they must be maintained and updated. Agentless means that it runs without a formal instal. It preforms the check, then disappears. This does mean that you will only be notified if it’s running.

SIEM (Security information and event management)

SIEMs are used to log security events and information. They are great for making reports for how security devices are doing. A SIEM is also used to create forensic reports for analysing. 

DLP (Data loss prevention) is used to find and block data that you do not want running on your network. For example, if someone is sending their card number, you can block it using a DLP solution. 

This prevents data being leaked from the network. This is great if you are worried than an attacker will try to take information from your network. 

SNMP = Simple network management protocol

Depending on the device you are using, there is a specific amount of data being collected a database called a MIB (Management Information Base). This database contains OIDs (Object Identifiers). 

This means that you are constantly querying devices like a router to see how much data is being sent in and out of a network. This allows you to compare times to detect high traffic volume in unexpected times. 

To get additional information on data that is passing over the internet is to use netflow. 

Netflow is a standard for monitoring traffic flows and looking at statistics related to application usage.

Netflow uses a probe that might be included in the software or an inside of a switch  by connecting to the monitoring port or there is a physical tap on the network that is providing the information. 
