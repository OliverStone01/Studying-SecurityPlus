#### 🎓 Professor Messer Study Notes

## Intrusion prevention - CompTIA Security+ SY0-701 - 3.2

[Link to video](https://youtu.be/7QuYupuic3Q?si=5UG9kNZSCcIb3soU)

### Notes

IPS = intrusion prevention system

An IPS is set to watch network traffic traversing the internet in real time. It looks for and blocks malicious activity and exploits. 

IDS intrusion detection system

The IDS is only an alert and will not block any malicious activity it finds. 

Although we want these device running 100% uptime, they do sometimes fail whether it’s from it breaking or a bug in the code. 

These devices are placed inline between the devices and the internet. For example:
Internet -> firewall -> IPS -> core switch

If the device has been setup as fail-open, then if the device fails, the traffic can still flow but with no protection. 

If the device is setup with fail-close, the traffic will not pass through if the device fails.

Some organisations believe IPS can be too invasive and can block good traffic. Instead these organisations use Passive monitoring.

An IDS can we set up by placing a switch inline that copies the data and is connected and passes this data to an IPS device. This device can still detect the malicious code but will not stop the data. 

Active monitor = IPS inline blocking malicious data

Passive monitor = Switch inline passing to an IPS device.

