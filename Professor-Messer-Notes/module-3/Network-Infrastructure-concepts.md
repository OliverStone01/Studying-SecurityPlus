#### 🎓 Professor Messer Study Notes

## Network Infrastructure Concepts - CompTIA Security+ SY0-701 - 3.1

[Link to video](https://youtu.be/jd001Hj7XWM?si=Kz2h5OYg3MsM5hmc)

### Notes

A main concern with network security is the ability for an attacker to move from one device to another.

We a use physical isolation such as air gaps where we have two devices not connected at all to each other. This means the attacker cannot get access to device a if they gain access to device b.

You may see this with web servers and databases where the web server is in one rack and the database is in another.

You might also see that companies that manage security may have one customer on one switch and another customer on the other switch to create an air gaps.

This method would mean that you need one switch per customer which will get expensive as you scale. 

Instead, we can use a VLAN on the same switch.

VLAN = virtual local area network.

A VLAN allows you to configure your switch into segments of virtual networks. VLAN’s are unable to talk to each other directly making a similar effect as physical separation.

Network devices like switches and routers are doing multiple operations at the same time. These are called the planes of operation. 

According to SDN (Software Defined Networking) there are three planes of operations:
- data plane
- control plane
- Management plane

The data plane is the one doing all the hard work. When we say data being routed or forwarded, encrypted, processing frames, etc. That is all done in the data plane.

The control plane manages the data transfer from one device to another. This includes sorting where the data should be going and how data can get from point a to point b.

The management plane is where you are able to make configurations and changes to this device and how you connect via SSH, browser, or via an API connection. 

Thanks to SDN we can do all this dynamically on our cloud networks at a click of a button. 
