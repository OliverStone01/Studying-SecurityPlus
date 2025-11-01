#### 🎓 Professor Messer Study Notes

##  Firewall types - CompTIA Security+ SY0-701 - 3.2

[Link to video](https://youtu.be/mq1HRM-zGtQ?si=XngQjEayrnKtlClE)

### Notes

Firewalls are used to control the flow of network traffic between two points.

Firewalls are great for controlling what sites and content a person may access on a device. They are also great at preventing malicious data being sent to the device. 

Network based firewalls can filter traffic by port number or application. Traditional firewalls operate on the OSI layer 4. However, newer generation firewalls operate on layer 7. 

Firewalls can also encrypt traffic between sites. 

Most firewalls can be used as layer 3 devices (Routers) by sitting at the edge of a network and control the traffic flow between the internal and external network.

They also have the ability at level 3 to have use Network Address Translation (NAT) functionality.

Older Firewalls would come as an all in one security device known as a UTM (Unified Threat management). Sometimes known as a Web security gateway.

These devices would feature: 
- URL filtering
- Malware inspection tools
- Spam filter
- CSU/DSU 
- Router/Switch
- Firewall
- IDS/IPS
- Bandwidth shaper
- VPN endpoint

The issue with UTMs is that most only operate at layer 4 and the device could not do all the above features at once due to low processing abilities. Turning on too many of the features would cause the device to slow down.

The modern firewall is a NGFW (Next Generation Firewall).

These devices work at layer 7 (Application layer).

These devices are also known as:
- Application Layer gateway
- Stateful multilayer inspection
- Deep packet inspection

These new firewalls are able to look and analyse all packets sent over the network which is then categorised into whether it is allowed or disallowed.

Network based NGLW’s will control traffic based on the application in use (Microsoft SQL server, twitter, YouTube)

You can filter content and prevent users from accessing certain sites depending on what the content is on that site. 

WAF (Web application firewall) analyse input into web applications and allow or disallow depending on what the input is. This allows you to detect SQL injections and block the command being sent to the web server.


