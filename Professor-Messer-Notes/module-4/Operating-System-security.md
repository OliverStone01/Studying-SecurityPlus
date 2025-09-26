#### 🎓 Professor Messer Study Notes

##  Operating System Security - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/4dpTyRM6BU8?si=zDBxNPOz_9jSVHHV)

### Notes

If you are working in an environment with many windows devices, you are probably using Active Directory. 

This database contains all the different components of your network (printers, computers, etc.)

From this centralised directory, we can manage authentication and determine which users can access what resources. 

We can also create groups of users and assign permissions to the entire group. 

We can create an apply policy’s to the Active Directory. This is called group policy and it is managed from the group policy management editor. 

From here we can create login scripts, network configurations, and other security parameters.

This helps create a comprehensive control policy.

For Linux, the default operating system works as a discretionary access control system (DAC). But if you are using these devices in an organisation, you may want a Mandatory Access Control system this allows you to control the devices and assign policies as a central administrator.

To enable this feature, we must install some patched that convert your system into SELinux (Security Enhanced Linux). This allows admin to set least privilege which will prevent attackers from manipulating systems they gain. 
