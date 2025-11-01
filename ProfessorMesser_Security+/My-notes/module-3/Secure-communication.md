#### 🎓 Professor Messer Study Notes

##  Secure Communication - CompTIA Security+ SY0-701 - 3.2

[Link to video](https://youtu.be/uU3e_ntg-3g?si=tRU_gpbW0xkkHG3d)

### Notes

A VPN (Virtual private network) encrypts all your data being sent over a public network from one point to another. The concentrator is the device the VPN will connect to creating an encrypted link/tunnel for the data to pass through. 

For example, our original packet may only contain the IP header where the data is being sent to the server and the data we want to send.

For tunnel mode, we have a New IP header for the correct VPN concentrator then we have the original IP header and data wrapped with a IPsec Header at the start and a IPsec Trailer a the end of the data.

If you are using a laptop or mobile device, you are likely using a SSL/TLS VPN.

SSL = Secure Socket Layer
TLS = Transport layer security

Some organisations will create a site-to-site IPsec VPN as it is designed to run in an always-on state. This means anyone working from home will be able to connect to the company network.

In this case, firewalls will often act as VPN concentrators for data to be passed between securely. 

A new form of wide area networks is SD-WAN (Software defined networking in a wide area network).

This was specifically designed for the challenges we have with connecting to cloud based applications. Previously, data was kept in one place but now it is all stored in the cloud. Using these wide area networks, we can now use applications from where ever we are in the world.

SASE = Secure Access Service Edge

SASE is the next level of VPNs that work with the new cloud based infrastructure. We would then only need to install SASE clients on our devices.

VPN - good for connecting remotely and transferring data remotely.

SD-WAN - for good connectivity to cloud based application. 

SASE - used to secure the connection with the SD-WAN.
