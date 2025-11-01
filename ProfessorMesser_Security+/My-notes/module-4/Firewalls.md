#### 🎓 Professor Messer Study Notes

##  Firewalls - CompTIA Security+ SY0-701 - 4.5

[Link to video](https://youtu.be/VgNyh4HEqSU?si=Z0os-i6S7I9yXhnS)

### Notes

A firewall that is inline with your network traffic will decide whether to allow or deny traffic depending on the rules we set.

We can filter traffic via port numbers or by application. There are 2 types of firewalls, traditional and NGFW (Next Generation Firewall)

There are other systems and functions that you can install on your firewall. For example, you can encrypt traffic which then turns your firewall into a VPN endpoint firewall.

Firewalls can also be configured as a router / layer 3 device. 

The next generation firewall works on applications (layer 7). We can then make decisions whether the data from that application is allowed to pass through or not. This is why you will commonly hear next generation firewalls being called application gateways.

Traditional firewalls make decisions based on what ports the data is using to get from point a to point b.

Most firewalls will have a list of rules which they will check against each time when deciding what to do with traffic.

This is why we put general or very specific traffic at the of the rule list.

A implicit deny means that if the firewall cannot detect any rules on the traffic, it will be denied when it gets to the bottom of the rule list.

Another name for a rule list is ACLs (Access Control Lists)

Most will put there firewall between the internet and their network/systems. This then separates the internet from your network with a secure wall. 

Screened subnet is a separate network from our internal network and contains devices that need to be accessed by the internet. The firewall then works as a router routing data to either the screened subnet or to the internal network.

This is great practice because if an attack manages to get access to the screened subnet, they do not have access to our sensitive data on our internal network.

Our IPS system also has rules and is usually integrated into a NGFW. The IPS is also monitoring the data passing and is looking for signatures that it recognises as malicious software. It also recognises injection and can also block these attacks.
