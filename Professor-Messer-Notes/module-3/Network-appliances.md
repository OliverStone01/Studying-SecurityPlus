#### 🎓 Professor Messer Study Notes

## Network-appliances - CompTIA Security+ SY0-701 - 3.2

[Link to video](https://youtu.be/WlOslEy3ztg?si=yO-3YTGnHVSp7_Z8)

### Notes

If you need to get access to devices from outside of the network, you can use a Jump server.

A jump server is a device on the network that is accessible from the outside of the network. This device is usually well secured to only give access to those authorised to do so. To do this, sometimes we use a two step process where the user connects to the jump server, then the jump server will use SSH or a VPN to make changes on the devices.

A proxy server is a device that sits between two devices and make requests on behalf of one of those devices.

This is commonly seen between a device and the internet. The device will send a request through the proxy server to the internet, the response is then checked through the proxy server for any malicious data and then sends the data to the device.

The proxy server can also cache information so that the device can access the data again without the need to make a request to the internet.

Proxies are also able to do URL filtering preventing the user from accessing specific sites.

An explicit proxy is one that needs to be configured in the application or the operating system.

A transparent proxy is a proxy that the end user does not know exists. It sits between two conversations and automatically configures and makes requests for the user.

A very simple proxy is a NAT. But the most used proxies are application level proxies. These proxies understands the application protocols.

Most proxies are multipurpose Andean be used for multiple protocols (HTTP, HTTPS, FTP)

A forward proxy is a proxy used to control outbound data to the internet. This is sometimes known as an internal proxy. 

A reverse proxy works the other way around for users on the internet that want to connect to a web server.

Reverse proxy also cache information so that if you make a request to a web server that has already been requested, you are sent back the information cached and you are not requesting each time from the web server. 

A open proxy is a proxy open to anyone on the internet. These are extremely insecure and are used in attacks.

A load-balancer distributes the requests made to a web server to help spread the load preventing the site from crashing and for better response times. 

Most load balancers are running in Active/Active mode. This means that all the servers are active and are being used. This also allows TCP offloading which means that it doesn’t need to create TCP connections to each server for each user. Instead it can reuse the same TCP connection.

The load balancer can also manage SSL encrypting and decrypting the data as it is sent back and forth.

Other land balancers will work in an Active/Passive mode. This means that some of the servers are ready to work and be used by the load balancer and there are other servers that are not currently being used. If the active server fails, then the balancer begins to send data to the server on stand by. 

Sensors and collectors are used on the network for intrusion prevention systems, firewall logs, authentication logs, etc.

The data from these sensors is then being sent to collectors. This might be a console (IPS, Firewall) or a SIEM console. A SIEM console allows you to report from many systems to one database and offers a powerful reporting tool.
