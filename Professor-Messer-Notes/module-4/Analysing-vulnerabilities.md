#### 🎓 Professor Messer Study Notes

##  Analysing-vulnerabilities - CompTIA Security+ SY0-701 - 4.3

[Link to video](https://youtu.be/eyVy1gKCuAU?si=n2k-GTkWQmK5dI_w)

### Notes

You will often find false positive which is information given to us about a vulnerability but after looking into it, the error does not exist. 

Given a positive, but turned out to be false.

A false negative is much worse because it means that at a vulnerability does exist but your detection system didn’t detect it.

It’s important to prioritise vulnerabilities. To check how vulnerable your system is after detecting, you can check a CVE list which will give you a severity score. It’s important to fix the most critical vulnerability’s first. 

CVE is the common vulnerability scoring system 

CVE (common vulnerability and exposures)

Each score ranges between 0-10. 10 being most critical. 

Your vulnerability scanner relies on signatures of  past vulnerabilities so it is important to keep this software up to date to detect the latest vulnerabilities. 

Vulnerability scanner can also scan applications and preform web application scans. It can also be used to scan the network for misconfigured firewalls, open ports, and vulnerable devices. 

An exposure factor is the quantification of how risky the vulnerability is to the network and system. 

This factor is usually represented by a percentage. If the vulnerability will effect the functionality of the system or network for 50% of the time, this would be given a 50% exposure factor.

A buffer overflow would have an exposure factor of 100%.

You need to look at the environment where the vulnerability is. For example, an internal server, a public cloud, or a test lab. How you will deal with patching these systems will vary between the two.

We must also prioritise which device is patched first. We start with the system that has the highest exposure factor and is in a vulnerable environment like a database.

To determine how important a system is, we must look at the number and type of users that connect to that device. We must also look at how much revenue the device is generating.

Some exploits have significant consequences depending on the type of organisation is effected. For example, a hospital being hit with ransomware can affect the care of patients. 

When patching devices and systems, it’s important to patch the right systems first. 

A Risk tolerance is prioritising which devices/system should be patched first. 

We cant just patch the system, we must test to make sure the patch is not going to break the system. 
