#### 🎓 Professor Messer Study Notes

## Segmentation and Access control - CompTIA Security+ SY0-701 - 2.5

[Link to video](https://youtu.be/yDeDGCh_PDs?si=wFScXcp9Z9Mp62eR)

### Notes

In order to control how much data an attacker can get when attacking your system, you can segment your network into different areas limiting the access between them.

This segmentation can be done physically, logically, or virtually.

Segmentation also helps with performance.

You may also be required to split up your network for compliance reasons like PCI (Payment).

To create these separations, we can use ACL’s (Access control lists)

ACL lists allow or disallow traffic based on the source IP, the destination IP, Port number, time of day, and the application.

You can also use ACL’s to restrict access to network devices.

It is important to take care when creating these ACL’s because you don't want to lock your self out while setting it up.

To set these up, you need to list the permissions.

Many operating systems use ACL’s

You may create an allow list on a device that only allows specific software to run on the device. Everything else will be rejected.

A deny list allows everything but the applications on the deny list.
